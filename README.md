# testProject
# DB_Script
CREATE DATABASE chatlogs;
create table chatlogs.users(
msgid int NOT NULL AUTO_INCREMENT primary key,
user varchar(16) NOT NULL,
msg varchar(45), 
time DateTime,
isSent tinyint);
