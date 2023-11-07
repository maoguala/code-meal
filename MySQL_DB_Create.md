CREATE USER '(自己)'@'localhost' IDENTIFIED BY '(自己密碼)'; 
CREATE DATABASE (自己資料庫);
GRANT Alter,Create,Delete,Drop,Index,Insert,References,Select,Update ON (自己資料庫).* TO '(自己)'@'localhost';
FLUSH PRIVILEGES;
exit;