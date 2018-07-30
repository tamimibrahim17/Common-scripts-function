### Commands

* Sort folder by size in a directory
```du -sk * | sort -n``` 

Create mysql user and grunt all prev..

* create user
```CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';```

* grant
```GRANT ALL PRIVILEGES ON * . * TO 'newuser'@'localhost';```

* reload
```FLUSH PRIVILEGES;```