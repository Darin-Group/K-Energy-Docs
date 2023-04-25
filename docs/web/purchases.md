This is where [Products](/web/products) are purchased from [Vendors](/web/contacts/#vendors).


### Purchase Order
A purchase order is the starting point of a Purchase. It is created by defining a Date, a Vendor, and optionally (An Estimated Delivery Date).


### Order Items
These are the actual purchased product lines. Below are some considerations regarding `Order Items`:   

* An Order Item can have one or more `Shipment` Records.
* One or More Order Items can be invoiced under the same Invoice Number


### Invoices
One or more `Order Items` can be invoiced under the same Invoice Number.
Purchase Invoices are issued by `Vendors` and are marked as Due until the full amount is paid.

### Shipments
A Shipment is a record of a product being shipped from the Vendor to the company. 
It is recorded against an Order Item. Once recorded, the shipment goes through several steps until fuel is unloaded to a Storage Tank. A typical shipment goes through the following steps:

* `Waiting`: Indicates that the shipment has just been created.
* `Arrived`: Indicates that the shipment has arrived at the company.
* `Sample Testing`: Indicates that the shipment is being tested for quality.
* `Sample Approved`: Indicates that the shipment has passed the quality test.
* `Fueling Out`: Indicates that the shipment is being unloaded to a storage tank.
* `Completed`: Indicates that the shipment has been fully unloaded to a storage tank.

### Payments
Payments can be made agains Invoices. And invoice can be fully paid by recording one or more Payments.