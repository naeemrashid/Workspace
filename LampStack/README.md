## Installation Steps
 ``` Ruby
    vagrant up
 ```
## Included Packages
+ apache2
+ python-mysqldb
+ mysql-server
+ php5.6

# Change mysql-server root password
```
cd defaults/
vi main.yml
mysql_root_pass: YourPassword #MySQL Root Password
```

## Test Installation
```
http://localhost:8080/info.php
```
