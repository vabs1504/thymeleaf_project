show databases;
create database blueyonder3;
use blueyonder3;
show tables;
select * from tutorials;

databse used:blueyonder3 
tables used:tutorials 

table structure:
Integer id(Auto generated value);
String title;
String description;
int level;
boolean published;

api used:
/tutorials - for all tutorials 
/tutorials/new - to add new tutorial
/tutorials/{id}- to search a tutorial by id 
/tutorials/delete/{id}- to delete a tutorial by id 
