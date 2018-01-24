```bash
$ sudo mysql
```

```sql
use mysql;
update user set authentication_string=PASSWORD("") where User='root';
update user set plugin="mysql_native_password"; 
flush privileges;
quit;
```
