# Botkeeper

## Task
* Building a NodeJS service to aggregate data from two different apis and then return it to the user. <br>There is a products api and an inventory api, they have the following api endpoints: 

### Inventory Endpoints: 
* /inventory - returns the inventory for all the products we have
* /inventory/name - returns the inventory for a single product 

### Product Endpoints: 
* /products - returns the all of the products and their prices 
* /products/name - returns a single products and its price
* The base url is http://autumn-resonance-1298.getsandbox.com

### What needs to be built: 
#### Create two api endpoints in NodeJS service to do the following:

* An api endpoint for the user to get all of the products along with each products inventory. <br>It should return an array of products that include the product's name, price and inventory.
* An api endpoint for the user to get a single product and have it return the product name, price and inventory. 
* There is no authentication or authorization required to access the apis. 
