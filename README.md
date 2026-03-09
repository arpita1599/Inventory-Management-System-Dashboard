# Inventory-Management-System (Excel) 
## Project Overview
This project is a simple *Inventory Management System built using Microsoft Excel*.  
It helps manage products, customers, vendors, purchases, and sales while tracking inventory automatically.

The system uses different Excel sheets and formulas to record transactions and update stock levels. Dashboard provides a quick summary of inventory activity.

## Features
- Product management
- Customer records
- Vendor records
- Purchase tracking
- Sales tracking
- Inventory monitoring
- Dashboard overview with summary data

## Tools Used
- Microsoft Excel
- Excel formulas
- Data tables
- Dashboard charts

## Sheets Included
1. *Dashboard* – Displays summary of inventory and sales.
2. *Customers* – Stores customer information.
3. *Vendors* – Stores vendor/supplier details.
4. *Products* – List of available products.
5. *New Entry* – Used to add new products.
6. *Purchase* – Records purchase transactions.
7. *Sales* – Records sales transactions.
8. *Inventory* – Tracks product stock levels.

## How It Works

The Inventory Management System works by recording product information, purchases, and sales in different Excel sheets. Excel formulas automatically update the inventory and display the summary in the dashboard.

### 1. Adding Products
First, product details are added in the *Products* sheet.  
Each product contains information such as:
- Product ID
- Product Name
- Category
- Price
- Vendor

This sheet acts as the main database for all products in the inventory.

### 2. Recording Customers and Vendors
The *Customers* sheet stores customer information such as customer ID, name, and contact details.  
The *Vendors* sheet stores supplier details used when purchasing products.

### 3. Recording Purchases
Whenever new stock is purchased, the details are entered in the *Purchase* sheet.  
This includes:
- Product ID
- Purchase date
- Quantity purchased
- Vendor name
- Purchase price

This data increases the available stock in the inventory.

### 4. Recording Sales
When a product is sold, the transaction is recorded in the *Sales* sheet.  
This includes:
- Product ID
- Sales date
- Quantity sold
- Customer name
- Sales price

This data decreases the available stock.

### 5. Automatic Inventory Update
The *Inventory* sheet uses Excel formulas to calculate the current stock level by comparing total purchases and total sales for each product.

Stock calculation example:

Current Stock = Total Purchased Quantity − Total Sold Quantity

### 6. Dashboard Summary
The *Dashboard* sheet displays a summary of the inventory using tables and charts.  
It provides insights such as:
- Total products
- Total purchases
- Total sales
- Current stock levels

This allows users to quickly monitor business activity and inventory status.

## Author
Arpita
