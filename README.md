# MySql_Queries

MYSQL CRUD;
C => CREATE
R => READ
U => UPDATE
D => DELETE


< ---    Data Definition Language --- >

CREATE , ALTER , DROP , TRUNCATE , RENAME

CREATE DATABASE Practice;
CREATE TABLE users(
	id int PRIMARY KEY AUTO_INCREAMENT;
	Name varchar(50),
	Email varchar(50),
	Salary int,
	Cities int
);
RENAME TABLE Practice TO My_Practice;
ALTER TABLE users ADD COLUMN age INT;
ALTER TABLE users CHANGE COLUMN age new_age int;
ALTER TABLE users DROP COLUMN new_age;
TRUNCATE TABLE users;
DROP TABLE users;
DROP DATABASE practice;

< ----  END DDL Queries  ---- >


< ---    Data Manipulation Language --- >
