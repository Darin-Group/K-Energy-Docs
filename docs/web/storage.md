This section is where the `Storage Units` are defined and the transactions between the `Storage Units` are logged.   

A Storage Unit can be of one of the below types:  

* Storage Tank: Stationary Tanks used to store fuel.
* Truck: Trucks that are used for transfering fuel.


!!! note "Warehouses"
	Warehouses are the physical location that both `Storage Tanks` and `Trucks` are kept.


### Transactions
Fuel is added and removed from the `Storage Units` using the `Transactions`.  Below are the different types of transactions:


* Received Shipment: Received from `Vendors`
* Outgoing Shipment: Sold to `Customers`
* Transfer: Transfer between two `Storage Units`
* Adjustment: Manual adjustment of the `Storage Units`
* Evaporation: Fuel that is lost due to `Evaporation`
* Waste: Fuel that is lost due to `Spillage` or other reasons.

### Recording Transactions
`Transfer` and `Adjustment` Transactions can be recorded right inside the `Storage` section as explained below.  

* `Transfer`: Open the `Storage Tanks` or `Truck` list and click on the `Transfer` button.
* `Adjustment`: Open the `Storage Tanks` or `Truck` list and click on the `Reconciliation` button.

### Confirming Transactions
All transactions are of a `Two-Step` nature. The first step is to record the transaction and the second step is to confirm the transaction.

!!! warning
	Transactions that are not confirmed appear in the `Transactions` list. A progress bar indicator and a confirmation button is displayed next to them.