### Overview ###

DeveloperHub Delete Order allows merchants to delete unwanted single or multiple orders with all of the linked data i.e. invoices, shipments, credit memos, and transections. Magento doesn't give the default functionality to delete orders. The store owners may want to remove unnecessary orders which have been canceled, closed, or created just for testing purposes. Delete Order by DeveloperHub can resolve that issue.

Merchants can delete unwanted orders with linked data of all kinds i.e. invoices, shipments, credit memos, and transections in bulk (via the mass action dropdown in Orders Grid) or one-by-one (via the Delete button on the Order Details page). In that way, merchants can enhance their efficiency, increase productivity, and speed up order processing in the store.

 

### Features ###

Allow the merchant to delete a single order as well as to delete orders in bulk.
Delete all the invoices from the deleted order.
Delete all transactions from the deleted order.
Delete the Credit Memo from the deleted order. 
Delete the Shipment of the deleted order.
Automatically delete an invoice, shipments, credit memo, and other linked data along with deleted orders. 
 

### Three Ways To Delete Orders ###

* Delete Order Using Mass action on Orders Grid: In Delete Order, merchants can delete orders in bulk using mass action. Merchants just have to select all those orders which they want to delete, then apply mass action Delete Order(s). Before deleting the order, a popup will be shown to confirm the Action. If the merchant confirms this action, selected orders will be deleted from the store.
* Delete Order Using Action Column on Orders Grid: To delete a single order using the action column, merchants have to select the Delete option from the Action column in the orders grid. When the merchants will select the Delete option from the action column selector, a popup will be shown to confirm the delete action. Once the merchant confirms this, the order will be deleted from the store.
* Delete Order using Delete Order Button on Order Details Page: In Delete Order, merchants have the option to delete the order from the Order Details page. Delete Order button will show on the top right corner of the order details page. When the merchant clicks on the delete button, a popup will be shown to the merchant to confirm the delete order action. When the merchant will confirm this action, this order will be deleted.


## Installation

1. Please run the following command
```shell
composer require devhub/core
composer require devhub/deleteorder
```

2. Update the composer if required
```shell
composer update
```

3. Enable module
```shell
php bin/magento module:enable DeveloperHub_Core
php bin/magento module:enable DeveloperHub_DeleteOrder
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento cache:flush
```
4.If your website is running in product mode the you need to deploy static content and
then clear the cache
```shell
php bin/magento setup:static-content:deploy
php bin/magento setup:di:compile
```



#####This extension is compatible with all the versions of Magento 2.3.* and 2.4.*.
###Tested on following instances:
#####multiple instances i.e. 2.3.7-p4 and 2.4.5p1

