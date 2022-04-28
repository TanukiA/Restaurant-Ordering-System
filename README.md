# Restaurant-Ordering-System

This is a simple Java ordering system for restaurant called Rin Ramen where the waiter or waitress can use it to collect orders and generate bills. In this restaurant, the available menu is relatively simple, in which there are 3 types of main meals, 2 types of beverages and 3 types of side dishes. For each order, the customer can select one main meal among the 3 types, and either order or not order beverages and side dishes. Beverages and side dishes can be of any quantity. After an order is submitted successfully, a bill is generated with necessary information such as table number, date, time, item names, prices, quantities and calculated payment amount. 

**JavaFX** is used to create and deliver a desktop application. This program also implements the Decorator Design Pattern in designing how the order should be managed.

Prerequisites/Procedures to run this program:
- Use Apache NetBeans IDE.
- Download JDK of version 11 or above.
- Download JavaFX (version 18.0.1 is used to develop). Move the JavaFX SDK into the Java folder located in the local directory. After that, go to the “Properties” of the OrderingSystem project to add a new library with JavaFX JAR files and modify VM options (to match the path of JavaFX located).
- Finally, run the Main class. 



