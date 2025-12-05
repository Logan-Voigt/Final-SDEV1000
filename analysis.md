# Problem analysis

## What the project is about: 
The goal of this project is to design and develop an inventory management system for an made-up online retailer. The system must allow the retailer to track products, process sales and analyze sales data. Then go on to justify the thought process behind the algorithms that were chosen to be used.

## What does the system need to do:
The system needs to do the following:
- Store and maintain product information given in the CSV provided. (ID,name,price,quantity,ect…)
- Process sales and update inventory
- Apply discounts under certain conditions
- Make receipts of the customers purchases
- Generate statistical analysis and reports using the provided dataset 
- Identify trends and relationships from historical sales
- Use and justify different algorithms


## Breaking The System Into Modules

The system can be broken down into three main modules, each with inputs, outputs and responsibilities.

## Main modules and what their for:

## Module #1: Inventory Management Module
Main purpose - Store, update, search and organize product information

Major Responsibilities:
- Add new products
- Update existing products
- Remove discontinued products
- Search though products using both linear search and binary search
- Sort products using merge or bubble sort (with justification)
- Inputs: Product details (ID,Name, category, Quantity, Price)
- Outputs: Updated inventory, search results and sorted product lists.
YF
## Module #2: Sales Processing Module
Main purpose: Complete transactions while updating inventory
Y
Major Responsibilities:
- Accept purchase requests 
- Check inventory stock
- Update inventory stock after purchase
- Apply discounts under certain conditions
- Generate receipts (product name, quantities, prices, final total)
Inputs: Product ID’s, quantity needed and rules for discounts
Outputs: Updated inventory, receipt with information about purchase.

## Module #3: Reporting and Statistical Analysis Module
Main purpose: Analyze sales and report information

Major Responseabilities:
- Total revenue calculation
- Average transaction value calculation
- Most and least popular products
- Price-quantity correlation, relationship between cost and demand
- Probability of sale for each product
- Trend analysis
Inputs: Dataset rows, (from CSV)
Outputs: Numerical results, charts and intercepted insights. Can use data to create bar graphs, line graphs, pie charts, ect… for visualizations.









## High-Level System Flow

Simple overview of how modules connect:
- START
- Load Inventory
- Load Sales Data
- User input choice
- Manage Inventory
- Process a sale
- Generate reports
- If Manage Inventory Selected
- Add, Update, Remove, Search, Sort options
- If Process A Sale Selected
- Validate stock > Process purchase > Update inventory > Create receipt
- If Generate Reports Selected
- Do statistical calculations
- Use data to make visuals
- Return To Beginning
- END 



## Algorithm Justification And Summary

Linear search:
- Works on unsorted data
- Simple and reliable for small datasets
Binary Search:
- Requires sorted data
- Much faster on large datasets
Bubble Sort:
- Easy to use but slow
Merge Sort:
- Efficient for large datasets
- Uses divide and conquer method
- Needs more memory



## Optimization And Validation

The system can be validated using:
1. Test Data - using values with known outputs to test the system
2. Performance Testing - you can compare search and sort runtimes
These tests can be run on the system to find places to optimize as well as to check for functionality and reliability.

## Summary

The analysis on the system breaks it down into clearer, smaller modules where there are clearly defined inputs and outputs and responsibilities. The modules will share data but can be looked at independently for simplicity. This breakdown will help guide the pseudocode and flowchart design keeping this structured and understandable.

