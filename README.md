# testProject
# DB_Script
CREATE DATABASE chatlogs;
create table chatlogs.users(
msgid int NOT NULL AUTO_INCREMENT primary key,
user varchar(16) NOT NULL,
msg varchar(45), 
time DateTime,
isSent tinyint);

--------------------------------------------
POST :http://localhost:8090/users/
      {
    "user":"Sarthak",
    "msg":"first Import"
        }
GET: http://localhost:8080/users/1/3

