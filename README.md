# Pizzeria__Interactive_Dashboard

## About The Scenoria
The Client Ben is openning a new pizzeria in his town, he has given a project brief. 
The first part requires us to design and build a talor-made bespoke relational database for his business that will allow him to capture and store all important information and data that the business generates, this will in turn help Ben to monitor business performance in dashboards.

## About The Project - Client Brief - Ben's Pizzeria
Main Area of Focus:
- Orders
- Stock Control
- Staff

### Orders Data Required
Ben's
- Order Id
- Item name
- Item price
- Quantity
- Customer name
- Delivery address

Mine:
- Row ID
- Order ID
- Item name
- Item category
- Item size
- Item price
- Quantity
- Customer first name
- Customer last name
- Delivery address 1
- Delivery address 2
- Delivery city
- Delivery zip code

### Stock Control Requirements
- Wants to be able to know when it's time to order new stock
- To do this we're going to need more information about:
  - what ingredients go into each pizza
  - their quantity based on the size of the pizza
  - the existing stock level
- I'll assume the lead time for delivery by suppliers is the same for all ingredients

### Staff Data Requirements
- Wants to know which staff members are working when
- Based on the staff salary information, how much each pizza costs (ingredients+chefs+delivery)

## About The Dashboards Building

### Dashboard 1 - Order Activity

For this, we will need a dashboard with the following data:
1. Total orders
2. Total sales
3. Total items
4. Average order value
5. Sales by category
6. Top selling items
7. Orders by hour
8. Sales by hour
9. Orders by address
10. Orders by delivery/pick up

### Dashboard 2 - Iventory Management
This will be a lot more complicated than the orders. Mainly because we need to calculate how much inventory we're using and then identify inventory that needs reordering.
We also want to calculate how much each pizza costs to make based on the cost of the ingredients so we can keep an eye on pricing and PIL.
Here is what we need:
1. Total quantity by ingredient
2. Total cost of ingredients
3. Calculated cost of pizza
4. Percentage stock remaining by ingredient
5. List of ingredients to re-order based on remaining inventory
