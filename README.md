                                                              # Instacart Market Basket Analysis
                                                              
# Introduction

Instacart is an American company that operates a grocery delivery and pick-up service in the United 
States and Canada.
Instacart, a grocery-ordering and delivery app, aims to make it easy to fill your refrigerator and 
pantry with your personal favorites and staples when you need them. After selecting products 
through the Instacart app, personal shoppers review your order and do the in-store shopping and 
delivery for you. The company offers its services via a website and mobile app.

# Business Problem

Market Basket Analysis is a data mining technique that is very much helpful to increase sales, helps
us to give a better understanding of customer purchasing techniques. Using the purchase history
done over a period we try to suggest the items to the customer that could be reordered.
The major benefits would be an increase in sales and customer satisfaction. Using the data we try 
to determine the products that are brought together with which retailers can optimize product 
placement, they can provide better deals which would encourage the customers to purchase the 
items which they had not thought of buying. This would thus help increase sales.
Market Basket analysis also allows companies to identify the important products and frequently 
purchased products which could potentially hurt their business if they are unavailable. For example, 
let’s say we have predicted that so and so the product would be a part of these many users’ next 
order. This would help the companies to be aware of the availability of the product and make sure 
it’s available.

# Dataset Description

The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 
200,000 Instacart users. For each user, we provide between 4 and 100 of their orders, with the 
sequence of products purchased in each order. We also provide the week and hour of day the order 
was placed, and a relative measure of time between orders. or more information, see the blog post
accompanying its public release.
The dataset consists of several CSV files, including:
* 1. orders.csv: Contains information about the orders placed by customers.
* 2. products.csv: Contains information about the products available on Instacart.
3. order_products__prior.csv: Contains information about products in prior orders.
4. order_products__train.csv: Contains information about products in the training set of orders.
5. aisles.csv: Contains information about product aisles (categories).
6. departments.csv: Contains information about product departments.
