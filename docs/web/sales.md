This is where [Products](/web/products) are sold to [Customers](/web/contacts/#customers).


### Sale Orders
A sale order is the starting point of a Sale. It is created by defining a Date, a Customer, and optionally (An Estimated Delivery Date).


### Order Items
These are the actual sold product lines. Below are some considerations regarding `Order Items`:   

* An Order Item can have one or more `Shipment` Records.
* One or More Order Items can be invoiced under the same Invoice Number


### Invoices
One or more `Order Items` can be invoiced under the same Invoice Number.
Sale Invoices are issued by `K-Energy` to `Customers` and are marked as Due until the full amount is collected.

### Shipments
A Shipment is a record of a product being shipped from the `K-Energy` to the `Customer`. 
It is recorded against an Order Item. Once recorded, the shipment goes through several steps until fuel is unloaded to a `Customer's` Storage Tank. A typical shipment goes through the following steps:

* `Waiting`: Indicates that the shipment has just been created.
* `Fueling Out`: Indicates that the shipment is being unloaded to a storage tank.
* `Completed`: Indicates that the shipment has been fully unloaded to a storage tank.

### Payments
Payments can be made agains Invoices. And invoice can be fully paid by recording one or more Payments.