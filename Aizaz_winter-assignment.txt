1- select * from customers;
2- select CustomerID from Customers;
3- select CustomerID, CustomerName from Customers;
4- select ContactName, Address, City from Customers;
5- select Country from Customers;
6- select CustomerID, CustomerName, Country from Customers;
7- /* no OrderID field in table customers */
8- select CustomerID from Orders;
9- select CustomerID, EmployeeID, OrderDate from Orders;
10- select ShipperID, OrderID from Orders;
11- /* no Country field in table Orders */
12- select OrderDetailID from OrderDetails;
13- select ShipperName, Phone from Shippers;
14- /* no LastName, FirstName fields in table Customers */
15- select LastName, FirstName, Notes from Employees;
16- select BirthDate from Employees;
17- select EmployeeID, Photo from Employees;
18- select CategoryName, Description from Categories;
19- select ProductID, ProductName from Products;
20- select SupplierID from Products;
21- select Unit, Price from Products;
22- select Country from Customers;
23- select EmployeeID, CustomerID from Orders;
24- select * from information_schema.tables;
	/* there is only 1 table */
25- /* table is called cars. There are 1284 rows so 1284 records */
26- select make, model from dbo.cars where DriveTrain='All'; 
	/* 276 records were affected */
27- select Type, origin from dbo.cars where Origin='USA';
	/* 441 records affected */