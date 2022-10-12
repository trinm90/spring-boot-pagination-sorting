# spring-boot-pagination-sorting

docker run --name mysql-docker -p 3306:3306 -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql

CREATE DATABASE javatechie;

use javatechie;

CREATE TABLE PRODUCT_TBL (
Id int,
Name varchar(255),
Quantity int,
Price int
);

INSERT INTO PRODUCT_TBL(
Id,
Name,
Quantity,
Price
)
VALUES(
999,
'',
999,
9999
);