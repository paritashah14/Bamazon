# Bamazon
This is an Amazon-like storefront with MySQL. The app will  welcome customers to place  in orders and display stock from the store's inventory.

#1: Customer View

Running this application will first display all of the items available for sale. Include the IDs, names, and prices of products for sale.

The app will prompt users with two questions.

The first question will ask the user the ID of the product they would like to buy.
The second question will ask how many units of the product the user would like to buy

screenshot-1






Once the customer has placed the order, this application will check if your store has enough of the product to meet the customer's request.

If not, the app will log a phrase like Sorry, insufficent in stock!, and then prevent the order from going through.
However, if my store does have enough of the product, it will fulfill the customer's order.
This will update the SQL database to reflect the remaining quantity.
Once the update goes through, it will show the customer the total cost of their purchase.

screenshot-2

