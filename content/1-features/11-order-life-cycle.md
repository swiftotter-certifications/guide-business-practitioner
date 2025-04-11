## 1.11 Using native tools to manage the order life cycle

Order status can be customized (and often are), but understanding the core workflow is necessary before solutioning those changes.

**Order**

* A order is created and is in pending status until payment is confirmed

**Invoice** 

* Offline payments confirms payment has been received
* Online payments (credit cards) confirms funds have been captured
* If the credit card gateway is set to “authorize & capture” at order, the order will be invoiced when placed and it will be in processing status.

**Editing orders**

* Before an order in invoiced, you will be able to make changes to the order itself
* After an order is invoiced, you will only be able to update address information
* You can edit the customer's email at any point by editing the customer.  

**Shipment**

* Creating a shipment also creates a packing slip, which can be printed from the order or the order grid
* Once a shipment is created, address information can no longer be edited
* Once all items in an order are invoiced and shipped, status will show complete

**RMA (Commerce only)**

* If configured for the store and for the item on an order, a customer can request a return inside their account
* Return attributes can be created to track any information you want a customer to complete
* If configured for the store and for the item on an order, a customer can request a return inside their account
* Once the return is authorized, the customer can be provided a return label or be asked to mail the item back
* After the item is received, the return is marked complete and a replacement can be sent, a credit memo created for a refund (online or offline), or store credit can be issued 

**Further reading:**

* [Order Workflow](https://docs.magento.com/user-guide/sales/order-workflow.html)
* [Returns](https://docs.magento.com/user-guide/sales/returns.html)
