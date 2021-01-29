# Password changing error

## Description

Macos big sur 11.1 version에서 설치한 후 패스워드 변경 안되는 문제

```sql
mysql

MariaDB [mysql]> update user set password = password('trust1990!') where user = 'root';
ERROR 1356 (HY000): View 'mysql.user' references invalid table(s) or column(s) or function(s) or definer/invoker of view lack rights to use them
```
