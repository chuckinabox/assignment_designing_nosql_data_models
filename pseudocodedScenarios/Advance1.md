<!-- Your eCommerce business needs to keep track of products and their prices. The products each belong to a department. The business needs to keep track of revenue as product prices change over time. The business also needs to keep track of receipts of transactions and the number of units each product has in stock. -->

##products

*Product id: number*
* Up to 10 digits
*Product name: String*
* Up to 50 characters
*Product description: text*
* Up to 200 characters
*Product price: Number*
* Up to 5 digits eg. 999.99
*Product previous price: list*
* eg. [999.99, 888.12]
*Inventory count: Number*
* Up to 5 digits eg. 99999
*Department: string*
* Up to 50 characters

##transactions

*transactions number: number*
* Up to 10 digits
*Product*
  *Product id: number*
  * Up to 10 digits
  *Product Quantity: Number*
  * Up to 5 digits eg. 99999
  
