This project contains a well-structured SQL schema for an E-commerce system.  
It is part of a database design and learning exercise.

The schema includes:

users: Customers who place orders.
categories: Product category groupings.
products: Items available for purchase.
orders: Purchase orders made by users.
order_items: Items included in each order.

Relationships

- One user → many orders
- One order→ many order_items
- Each order_item → one product
- Each product → one category
