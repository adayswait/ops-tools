免密登录.sh
```
#!/usr/bin/env bash
sshpass -p'password' ssh -p56000 adayswait@10.1.1.1
```

登录mysql.sh
```
#!/usr/bin/env bash
clear
db="DB_01"
host="10.1.1.1"
user="adayswait"
passwd='password'
pmt='--prompt=\R:\m:\s-\U-\d-MySQL>'
charset='--default-character-set=utf8'
mysql -h$host -u$user -p$passwd $pmt $charset
```
