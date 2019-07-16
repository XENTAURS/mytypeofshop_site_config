# mytypeofshop_site_config
Database and image files for the MyTypeOfShop application

1. Copy FilesRepository.dat to /opt/infinispan/files/repos on both web servers
2. Copy StoreRepostiroy.dat to /opt/infinispan/files/store on both web servers
3. Copy the SALESMANAGER.sql file to the MySQL server and then run the following:
```
mysql -u root -p C1sc0.123 < SALESMANAGER.sql
```
