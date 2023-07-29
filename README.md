# About Ecommerce Project

## Brazilian E-Commerce Public Dataset by Olist
This is a Brazilian ecommerce public dataset of orders is shared by Olist, the largest department store in Brazilian marketplaces. 
The dataset has information of 100k orders from 2016 to 2018 made in Brazil. 

## Context
Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. 
Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. 

After a customer purchases the product from Olist Store, a seller gets notified to fulfill that order. 
Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

# Requirement
- Analyse the company's performance and deliver insights for improvement
- Provide rationale behind metrics
- Provide supporting analysis and visualization to communicate ideas

# Data overview
## Order Dataset
This is the core dataset showing order information that can be linked to other tables to find detailed information.

## Customers Dataset
This dataset has information about the customer and its location. Use it to identify unique customers in the orders dataset and to find the order delivery location.

Each order is assigned to a unique customer_id. This means that the same customer will get different ids for different orders. 
The purpose of having a customer_unique_id on the dataset is to identify customers that made repurchases at the store. 

## Order Items Dataset
This dataset includes data about the items purchased within each order.

## Payments Dataset
This dataset includes data about the order payment options.

## Order Reviews Dataset
This dataset includes data about the reviews made by the customers.

## Products Dataset
This dataset includes data about the products sold by Olist.

## Sellers Dataset
This dataset includes data about the sellers that fulfilled orders made at Olist. Use it to find the seller location and to identify which seller fulfilled each product.

## Category Name Translation
Translates the product_category_name to english.

# Solution
The code generating the result is conducted in Python.
Kindly find the notebook attached at the top of the page.  

# Result
