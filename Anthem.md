# Anthem 🧭
Names | Details
--------|-----
Source | tryhackme
Level     |  easy
Os | windows

**Notes :**




## Gaining Access 😉

- in robots.txt  we got "`Umbraco`IsTheBest!"
- since got  admin user name from poem and password from robot.txt
- now we can connect using rdp (https://book.hacktricks.xyz/pentesting/pentesting-rdp)
- ```xfreerdp /u:sg /p:UmbracoIsTheBest! /v:10.10.214.132```

C:\.backup\ have a file called restore (with no permission )
give some perm and read it "ChangeMeBaby1MoreTime"

## Maintaining Access 🥷
- 


## Important commands 🔥
- ``xfreerdp /u:sg /p:UmbracoIsTheBest! /v:10.10.214.132``

## Post Exploitation ✴️
- Flag1: view-source: THM{L0L_WH0_US3S_M3T4}
- Flag2: view-source: THM{G!T_G00D}
- flag 3:http://10.10.53.47/authors/ :THM{L0L_WH0_D15}
- flag 4:view-source: THM{AN0TH3R_M3TA}
- User flag : in desktop user.txt:THM{N00T_NO0T}
- Root flag : Administrator \ Desktop \  root:THM{Y0U_4R3_1337}
## Tips 💡
- something


--------------------------------
**By Whois~TCP ** 🤓🖥️






