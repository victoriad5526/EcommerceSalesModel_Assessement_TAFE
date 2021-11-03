# EcommerceSalesModel_Assessement_TAFE
Create a Database 

You have been employed as a contract database developer for an e-commerce website.  The site requires a new database backend to manage the purchase of the products available in their listings.  The store owner had a consultant commence the project and he completed a high level design before moving and leaving the owner with the limited documentation below.
The database produced must meet the requirements specified in the following documentation and the final design must be agreed between the database user and the database designer prior to physical creation.
Requirements
Entities required include:
•	Members
•	Products 
•	Orders
•	OrderLines

Entities are related as follows:
•	A Member can place many orders
•	A product can appear  in many orders
•	An Order can have many orderlines

The organisational Security Plan states:
•	All software applications must include a user logon
•	User logons are to be of  two types:
o	Business - which allows all the database creation and modification to be done,
o	EndUser  - that allows the front end functions  of creating and account, creating an oder and viewing order history.
 

Ecommerce  sales Model
The following data model is designed to hold information about orders:

![image](https://user-images.githubusercontent.com/37015468/140000539-1f6c07f5-a0b1-4fdc-8e64-f354b3f584be.png)
 
Conventions used in this model.
•	Entities are named with a single noun, except Order , which is a keyword in SQL and so it not allowed.
•	The primary key is the entity name with ID appended, except again, in the case of Order.
•	Each attribute takes a three letter code as a prefix to represent the entity to which it belongs, to avoid ambiguity of attribute names. This is often the first 3 letter of the table name, provided this is unique to the database.

=========================================================================================
Solution overview:

![image](https://user-images.githubusercontent.com/37015468/140001053-632fbc15-750a-4f7c-b163-be8e6aa0cb7d.png)


![image](https://user-images.githubusercontent.com/37015468/140001678-6c032891-f583-4e46-868c-1e53167c4204.png)



