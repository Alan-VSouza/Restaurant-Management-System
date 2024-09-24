# Restaurant Management System

This project is a system designed to be implemented in a restaurant in my city. It manages sales, inventory, and security, providing an efficient workflow for both managers and staff.

## Features

### Sales:
- Fetch dishes, prices, and quantities from the database ✅
- Add products to sales, specifying the quantity ✅
- Payment options: Credit, Debit, Cash, and PIX ✅
- If payment is by cash, calculate the change and validate the correct amount ✅
- Change the password by retrieving the previously registered one
- Generate an invoice for the customer
- Generate a sales report for a specified date range

### Inventory:
- Add new products to the stock ✅
- Remove products and update their quantities ✅
- Automatically place orders through Apache or signal low stock levels

### Security:
- Two user roles: Manager and Employee ✅
- The manager has full administrative access and can place orders
- Employees can only process sales and cannot generate reports
