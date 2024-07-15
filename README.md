# SQL_Class_Project
Overview on SQL final project I worked on while in college in my Database Management class. 
In this project we were instructed create a fake scenario in which we would take on the challenge on helping a existing company manage their data and databases for efficiency. We decided to work with Office Depot, a well known and large chain selling office & school supplies, electronics & furniture.

#Here is the overview on the group report we worked on: 

Company Overview:
Office Depot is a global supplier specializing in providing office supplies, office furniture, and technology products, including laptops, storage devices, and printers. With a strong focus on serving the needs of businesses, Office Depot offers a range of products and services designed to help customers efficiently manage and grow their operations.

Business Goals:
The primary business goal of Office Depot is to empower customers by providing essential resources and tools that enable them to focus on their passions while effectively running and expanding their businesses. This commitment to customer success drives Office Depot to continually enhance its product offerings and service capabilities.

Services Provided:

Office Supplies: A comprehensive selection of office essentials, from paper and writing instruments to organizational tools and cleaning supplies.
Office Furniture: A variety of furniture options designed to create comfortable and productive workspaces, including desks, chairs, and storage solutions.
Technology Products: Advanced technology solutions such as laptops, printers, storage devices, and other tech accessories to support modern business needs.
Online Orders and Delivery: An efficient online ordering system that allows customers to place orders for delivery or pickup, ensuring they receive their products conveniently and promptly.

User Requirements for the Group Project
To document the services provided by Office Depot and ensure efficient order processing and delivery, the following user requirements were identified for the SQL project:

Customer Information:
  CustomerID: Unique identifier for each customer.
  Name: Customer's last name and first name.
  Address: Street, city, state, and zip code of the customer's address.
  Card Information: Includes cardholder name, card number, expiration date, and CVV.
  
Order Information:
  OrderID: Unique identifier for each order.
  Date: Date when the order was placed.
  Shipping Address: Street, city, state, and zip code for the shipping destination.
  Quantity: Number of items in the order.
  Status: Current status of the order (e.g., pending, shipped, delivered).
  Order Type: Indicates whether the order is for delivery or pickup.
Warehouse Information:
  WarehouseID: Unique identifier for each warehouse.
  Warehouse Address: Street, city, state, and zip code of the warehouse location.
  
Employee Information:
  EmployeeID: Unique identifier for each employee.
  Name: Employee's name.
  SSN: Employee's social security number.
  Employee Type: Indicates whether the employee is a packer or a manager.
  
Vendor Information:
  VendorID: Unique identifier for each vendor.
  Vendor Name: Name of the vendor.
  Vendor Address: Street, city, and zip code of the vendor's address.
  Vendor Phone Number: Contact phone number for the vendor.
  
Product Information:
  ProductID: Unique identifier for each product.
  Product Name: Name of the product.
  Product Price: Price of the product.
  Product Description: Description of the product.
  Product Type: Type of product (office supplies, furniture, electronics, etc.).
  
Store Information:
  StoreID: Unique identifier for each store.
  Store Address: Street, city, state, and zip code of the store location.
  
Return Information:
  Receipt Number: Unique identifier for each return.
  Return Date: Date when the return was requested.
  Purchase Date: Date when the product was originally purchased.
  
#SQL Project Implementation
The SQL project involved designing and implementing a database to manage the information outlined above. This included creating tables for customers, orders, warehouses, employees, vendors, products, stores, and returns, as well as establishing relationships between these tables to ensure data integrity and support efficient queries and reports.

By documenting these user requirements and designing a robust database schema, the project aimed to streamline Office Depot's order processing and delivery system, ensuring accurate tracking and fulfillment of customer orders, efficient management of inventory, and effective coordination between various stakeholders.
