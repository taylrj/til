1. At the command line, log in to MySQL as the root user:
```
mysql -u root -p
```

2. Type the MySQL root password, and then press Enter.

3. To create a database user, type the following command. 
- Replace username with the user you want to create
- Replace localhost with the host from which you connect to the server. 
- Replace password with the user's password (now is 'password')

```
GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost' IDENTIFIED BY 'password';
```
