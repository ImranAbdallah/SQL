# SQL
SQL Portfolio
## Welcome to my SQL portfolio! This code repository contains examples of SQL I've written. Feel free to take a look and reach out if you have any questions.@abdulaziz1586@gmail.com
check out my sales database here. Notice how I've described each piece of code (first I created a sales database, then displayed the database ordered by different tables and columns) 





CREATE TABLE customers
(
   customer_id INT,
   first_name VARCHAR(255),
   last_name VARCHAR(255),
   email_address VARCHAR(255),
   number_of_complaints INT,
   primary key (customer_id)
);   



CREATE TABLE items
(
   item_code VARCHAR(255),
   item VARCHAR(255),
   unit_price NUMERIC (10,2),
   company_id VARCHAR(255),
   primary key (item_code)
);





CREATE TABLE companies
(
  company_id VARCHAR (255),
  company_name VARCHAR(255),
  headquaters_phone_number int (12),
  primary key (company_id)
);
