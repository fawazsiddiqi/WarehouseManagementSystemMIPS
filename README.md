# Warehouse Management System

The motive of the MIPS program which is produced by my group is to manage a company’s inventory system in which the company has 8 types of particular products which are stored in 8 different warehouses.

The user has a choice to perform various functions such are transferring the inventory from one warehouse to another, receive shipments, ship them to the customers, publish the inventory items and get an overview of the entire inventory with the calculated overall costing for the entire warehouse. The resolution proposed for this system is that we initialize 8 arrays which belongs to each of the warehouse in which the products are stored using a series of while and do-while loops.

For example, when we receive a shipment we enter R (or r) as an option in the menu, the user is then asked to enter the product number, the warehouse number to be stored in and the quantity of the product:(one value at a time) 
Input example:

1 enter

2 enter

3 enter

Thus, this means that PRODUCT 1 is to be added to WAREHOUSE 2 with the QUANTITY of 3.

This process takes place when product 1 is entered, it stores the address of warehouse1Arr (array of warehouse 1) into a register, after which it is forwarded to another function which is responsible for storing the product into the warehouse. 

The storing function is a while loop, in which it reads the warehouse as a comparison variable and a counter is also initialized which checks that it is it be stored in warehouse 2 and thus quantity of 3 of type product 1 is stored in the array. The user is also given an option to overview the entire inventory cost in which all the costs of all the products are added and the user can see the entire costing with the help of basic arithmetic’s.

Various validations and verifications are also added to the proposed programs so that it is not case sensitive for the ease of the user and also it makes sure that the user does not enter a value which is not accepted such as values which are less than or equal to 0 or in the case of warehouses the warehouse number is between 1 and 8 (inclusive) and the product number is between 1 and 6 (inclusive) and entering an invalid value will lead to an error informing the user that the entered value is not acceptable.
