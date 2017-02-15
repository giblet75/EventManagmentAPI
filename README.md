# EventManagmentAPI
EventManagementAPI

## Dependencies
### PostgreSQL - two instances
1. Download PostgreSQL - BigSQL package manager is a good option
https://www.bigsql.org/package-manager.jsp
This installs a package manager where you can actually install whatever version of postgres you want, etc.
Install pg96 as shown on the bottom of the page
2. Create users and databases:
```bash
$ createuser -P nuid
Enter password for new role: nuid
Enter it again: nuid

$ createuser -P user_data
Enter password for new role: user_data
Enter it again: user_data

$ createdb -O nuid nuid
$ createdb -O user_data user_data
$
```
