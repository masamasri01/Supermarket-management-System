# Supermarket-management-System

 Database for Supermarket 
Database class project 2020/2021

Abstract
Database supermarket project is related to the internal matters of the 
supermarket. This project was developed in order to obtain a safe, reliable, easyto-use and faster system to obtain benefits.
There are many reasons for doing such a project. Which initially helps the 
employees inside the supermarket, where each employee has his own number 
and password that he can enter through them. The manager can view all the 
employees and know their information as well as know all the existing products 
and buy them from suppliers, and thus he has the ability to know all details about 
the products. It is also possible to make an order that contains all the information 
and details needed about the products, the date and time of the order.

Introduction
Technology today has become very important due to the rapid development that 
is taking place and also with the increase in the spread of supermarkets here, the 
importance of having a database that works to store different data and access it 
in an easy and simple way, and this project will help a lot of medium and small 
supermarkets scattered everywhere. It is possible that a lot of errors occur during
the buying or selling process and thus getting problems. To avoid this the 
supermarket database project can be used, through which all products and their 
information are displayed, from price to available quantity, production and expiry 
dates, and through it also an order can be made containing the products, created 
by the cashier employee.
To know the information related to the employees, only the manager can access 
it, where he can view all the employees with their working hours and also update 
their data or remove them.
Through this project, we can obtain easy-to-use, structured data that saves time 
and effort, as well as safe.

<h> requirements </h>
In this project we have 4 entities, the first entity is the person then the market , the 
order and the product.
Database supermarket relates to, employees their working days, the orders they 
prepare. The customers and the products they choose to be placed in the list of 
orders. And the market responsible for purchasing products from the dealer
Each person in the Database has his own information, which is the name, address, 
ID, date of birth and phone number. There are two subclasses for the person, which 
are customers and employees, and the information of employees in particular are 
their number, salary, university degree and professional competence. The 
employees also have subclasses, and they are the cashier, deliveryman and 
manager.
The manager can deliver all orders and the cashier is the one who records the 
orders and the delivery service delivers them.
Each customer has his own points when purchasing. The points are increased to an 
extent that allows them to obtain a discount. The customer can have more than one 
order.
Products whose information is the name, product number, type of product, quantity 
and price. The merchant sells different products and also the products have more 
than one source
Finally, the order contains information for the order number, the order date, and 
the total price of the order.


 
UML diagram
![Screenshot (142)](https://user-images.githubusercontent.com/93089580/214302514-a0c0c5c4-bbd2-4a18-889e-721ff0f4e204.png)

Project Tools

Oracle Database : is a collection of data treated as a unit. The purpose of a database 
is to store and retrieve related information.
NetBeans IDE : We used this program to design interfaces and connect them with 
Database using the Java language
Jasper Report Studio:This program we used to create a report and then convert it to 
pdf with NetBeans IDE 


Discussion
![Screenshot (143)](https://user-images.githubusercontent.com/93089580/214303824-5197351b-adcd-41a8-9a5c-aa13a53b9696.png)

This is the first screen through which you can enter the system by 
1- Login as a Manager, you must enter the id number and his password . 
2- Login as a cashier also you must write the id number the password . 
On this screen there is also a button to see some of the available products
![Screenshot (144)](https://user-images.githubusercontent.com/93089580/214304012-6f4343ff-fd6d-4f81-805d-e628c2b9fa2a.png)

When entering as a manager, this screen appears that consists of 5 buttons, the first one goes to 
employee information, the second one goes to supplier information, the third one is about product 
information, the fourth is about order information, and the last button is to go back to the previous 
screen.
![Screenshot (145)](https://user-images.githubusercontent.com/93089580/214304256-16dfc308-119a-4bcd-83dd-034aa75e0304.png)

![Screenshot (147)](https://user-images.githubusercontent.com/93089580/214304815-2250106a-391b-4d33-8cba-39317a129fa9.png)

This screen appears when pressing the employee info button. 
This screen enters the employee and takes the information with the possibility of removing the 
employee by typing his id number and then pressing the fire employee button. Through this screen also, 
all employees can be displayed according to a specific date and select the shift type. As for the existing 
button At the top, you can go to other screen to display the employees, and the back button at the 
bottom to go back to the previous screen

 ![Screenshot (148)](https://user-images.githubusercontent.com/93089580/214305007-fa2bbc16-5565-4652-9b51-c0d83c33ecdd.png)

When pressing the “Suppliers Info” button, this screen appears, which includes three buttons, 
the first to search for a supplier, the second to buy products from the supplier, and the last 
button to return to the previous screen
This screen when we click on the list of all employees The first button can show all cashiers
The second is for show all security officer Then the back button to return to the previous screen
14
![Screenshot (150)](https://user-images.githubusercontent.com/93089580/214305311-1ff6b292-bf89-4d75-9050-c4992ebcaf34.png)

After pressing the search for supplier button, this screen appears. 
We enter the id number of the supplier within the filed text, then click on search by id. The name, 
number and address of the supplier appears. We can return to the previous screen by pressing back
![Screenshot (151)](https://user-images.githubusercontent.com/93089580/214305481-a2995074-a0ab-46a3-808c-9ac5476fa1de.png)

By pressing the "Buy from supplier" button, this screen appears, through which the products that belong 
to the supplier are first displayed. The search is done by the supplier ID number. The products are 
displayed in the text area after pressing the display button The second part is to choose one of the 
products and write the product ID in the text field, price and quantity, click on the button to buy from 
the supplier. Purchased at the end of the screen. Back button.
15
![Screenshot (152)](https://user-images.githubusercontent.com/93089580/214305674-020d45aa-c2e0-433c-bc9d-543a81b5b3c7.png)

From screen No. 2 after pressing the “products info” button we see this screen
that first displays all the products in the supermarket when you press the” list all products available at 
supermarket” button You can also change the discount rate and price. At first, you must write the 
product id, then write the discount rate and press the change discount rate button To change the price. 
Click on change price and you can also you can delete a product by “Delete product” button and return 
to the previous screen through the back button

![Screenshot (153)](https://user-images.githubusercontent.com/93089580/214305957-1e35c225-8980-42ca-b8fa-443353cd65fe.png)

From the main screen and when entering as a cashier, this screen appears that creates an order by 
entering the customer ID number and specifying the payment method, then entering the products that 
he wants to buy on Text Aria then cashier id number price and Date back appear on screen then “Bill 
pdf” button make order as pdf to go back to the previous screen
![Screenshot (154)](https://user-images.githubusercontent.com/93089580/214306170-29fe5ab1-56a4-4522-af85-c91da947cc38.png)


![Screenshot (155)](https://user-images.githubusercontent.com/93089580/214306352-fed9676d-dbca-42e3-a8ff-ef8076d3c3f6.png)

“Order info”
This screen displays all the orders created by the cashier where once you enter the cashier id And 
pressing get, all orders will be shown. It also has a button to know the most selling products and another 
button to find out the most customers who visit the supermarket
