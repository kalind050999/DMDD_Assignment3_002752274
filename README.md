# DMDD_Assignment3_002752274
Assignment 3: Gathering, Scraping, Munging, and Cleaning Data
Project Name – Grocery Invoice Billing Management System
Member Name – Kalind Joshi
NUID – 002752274

* empclean and empclean1 are two notebooks which clean employee data
* finalemp is the notebook which will merge and create final empcleaned file i.e. finalemp.xls
* employeeinsert.sql is the sql file to push empclean.csv data to mySQL DB
* prodclean1 is the notebook which clean product data from groceriesdataset.csv and will create a cleaned xls file i.e. prodclean.xls
* productimport.ipynb is the notebook which import the prodclean.xls file to the SQL database
* invoicefinal.xls is a combination of all the other tables like product, customer etc.
* invoiceimport.ipynb is the notebook which will import the invoicefinal.xls to mySQL database
* custclean1.ipynb is the notebook which will clean Customer_Names.csv and generate a cleaned file which is named as custclean.csv
* customerinsert.sql is the sql file to push custclean.csv data to mySQL DB
* invoicedataupdate.sql will update the date values in the invoice  table 
* SQLQueries.sql has the sql queries which are of the 5 use cases
* ProdEDA has auditing of product table 
* OtherEDA has auditing of rest of the tables

Based on review received from assignment 2 code, I have changed the column names to full names
