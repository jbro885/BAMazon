# BAMazon

Created during Week 12. The goal was to create an Amazon-like store front using Node.js and MySQL.

## Getting Started
-----------------------

### What Each JavaScript Does

1. `BamazonCustomer.js`

    * Prints the items in the store.

    * Prompts customer which item they would like to purchase by ID number.

    * Asks for the quantity.

      * If there is a sufficient amount of the item in stock, it will return the total for that purchase.
      * However, if there is not enough of the item in stock, it will tell the user that there isn't enough of the product.
      * If the purchase goes through, it updates the stock quantity to reflect the purchase.

2. `BamazonManager.js`

    * Starts with a menu:
        * View Products for Sale
        * View Low Inventory
        * Add to Inventory
        * Add New Product
        * Remove Product
        * End Session

    * If the manager selects `View Products for Sale`, it lists all of the items in the store including all of their details.

    * If the manager selects `View Low Inventory`, it'll list all the items with less than five items in its StockQuantity column.

    * If the manager selects `Add to Inventory`, it allows the manager to select a product and add inventory.

    * If the manager selects `Add New Product`, it allows the manager to add a new product to the store.

    * If the manager selects `Remove Product`, it allows the manager to remove a product from the store.

    * If the manager selects `End Session`, it ends the session and doesn't go back to the menu.


3. `BamazonExecutive.js`

    * Starts with a menu:
        * View Product Sales by Department
        * Create New Department
        * End Session

    * If the manager selects `View Product Sales by Department`, it lists the Department Sales and calculates the total sales from the overhead cost and product sales.

    * If the manager selects `Create New Department`, it allows the manager to create a new department and input current overhead costs and product sales. If there are none, by default it will set at 0.

    * If the manager selects `End Session`, it ends the session and doesn't go back to the menu.

## Demo Videos

* BamazonCustomer.js ()

* BamazonManager.js ()

* ExecutiveManager.js ()

## Technologies used
- Node.js
- npm inquirer (https://www.npmjs.com/package/inquirer)
- npm mysql (https://www.npmjs.com/package/mysql)

### Prerequisites

```
See package.json
```

## Built With

* Sublime Text - Text Editor
* MySQLWorkbench
* Terminal/Gitbash

## Authors

* **Stefanie Ding** - *JS/MySQL/Node.js* - [Stefanie Ding](https://github.com/StefanieDing)