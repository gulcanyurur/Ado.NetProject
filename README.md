Ado.Net project in C# using Visual Studio, I utilized the Express version of SQL Server for my database. Firstly, I created my database and named it ETrade. I then created a table within it and entered my products with the columns (Id, Name, UnitPrice, StockAmount).

I opened a form screen and used a grid. I created my classes and opened a class named "ProductDal" to perform database operations. For entering products, I created a class called Product.

I wrote a method that retrieves the products. I set up my SQL database connection. Opening the connection using if blocks, I later refactored it into a method for a cleaner appearance.

I initiated a query, sent it to the connection, executed the command, and went to the class of my Data Grid, referencing my ProductDal class. As a data source, I called my GetAll method from ProductDal. I created a Product list to store the result.

Using a While loop, I made sure the reader reads each record and assigns them to the loop one by one. I transferred each element I read to a product and added it to the list. After closing the connection, I returned the list.

I created a group box, added an add button to it, and assigned its click event to a method called "Add" where I wrote the insertion command with parameters and values.

I called my values to the Add button, wrote the method for my update operation, added the update area to my design, assigned events to my button, wrote the method for the delete operation, and added a button, assigning an event and writing the code.





