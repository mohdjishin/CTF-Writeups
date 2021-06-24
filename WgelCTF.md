# WgelCTF 🧭
Names | Details
--------|-----
Source | tryhackme
Level     | easy
Os |linux

**Notes :**




## Gaining Access 😉

- found username in Source code
- got ssh private key in subdirectory (id_rsa)
- cracked it
- change permission ``chmod 600 id_rsa``
- got access 🙌


## Maintaining Access 🥷
- ``sudo -l``  found wget in no passwd list
- there is a way to replace passwd file using wget
- create a dup passwd in local machine
- ``openssl passwd anypassword``
- insert the hashed  password in root (x)
- ``sudo wget file -o /etc/passwd 
- now su root and password,
- got root!!


## Important commands 🔥
- ``chmod 600 id_rsa``
- ``openssl passwd anypassword``
- ``sudo wget file -o /etc/passwd

## Post Exploitation ✴️
- User flag : /home/user/Documents/user_flag.txt
- Root flag : /root/root.txt
## Tips 💡
- something


--------------------------------
**By Whois~TCP ** 🤓🖥️






