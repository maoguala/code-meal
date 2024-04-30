CREATE USER 'Myself'@'localhost' IDENTIFIED BY 'Myself_pass'; 
CREATE DATABASE My_own_DB;
GRANT Alter,Create,Delete,Drop,Index,Insert,References,Select,Update ON My_own_DB.* TO 'Myself'@'localhost';
FLUSH PRIVILEGES;
exit;
