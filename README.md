# Inventory_Management_System
I have made an Inventory Management System using Python Programming Language applying the concepts of JSON and File Handling during my Internship at Elite Techno Groups. This Inventory Management System maintains the data of sales generated throughout the day and also has a billing program where the owner can provide a print of computerized bill to the customer.

### It is an Inventory Management System which works on NoSql based Database.

### The product details that user will be adding using the (adding_items_to_inventory.ipynb) program will be stored in (item_records.json) file
The details one needs to input for adding a new product in the inventory are as follows:
1) Product Id
2) Name of Product
3) Price of Product
4) Quantity present
5) Expiry Year
 
### On successfully adding items in the inventory access the (item_records.json) file and upload it for the program (purchase_from_inventory.ipynb) in order to access the products present in the inventory.
1)In (purchase_from_inventory.ipynb) program the user will be asked to enter the name of the customer and the no.of items customer wishes to buy.

2)After that the user is asked to input the Product id and the quantity of the item customer wants to buy which is the billinh code in the (purchase_from_inventory.ipynb) program.

3)After all the items are added to the cart,A bill with name of the customer,day,date and time will be present in (bill.txt) file, of which the user can provide computerized print of the bill to the customer(After executing the billing code present in (purchase_from_inventory.ipynb) program for the first customer of the day only execute the billing code there after till its the last billing of the day in orderto get the total sales of the day in one go).

4)After all the sales of the are over execute (The Sales Code) program section present in (purchase_from_inventory.ipynb) program and all the sales that were generated and the amount earned throughout the day will be stored in (sales.txt) file.


