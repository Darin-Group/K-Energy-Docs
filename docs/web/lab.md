### Sample Tests
A `Sample Test` is a test that is performed on a sample of a product.  
Tests are performed on products that are `Purchased` from `Vendors`.  

An incoming shipment from a Vendor can not be unloded until an `Approved` Sample Test is recorded.



### Library
The Library is where the parameters other related data are defined. It contains below:

* Test Parameters: This is the `Main` item that's needed for lab tests.
* Test Units: Optional fields that can be attached to `Test Parameters`.
* Test Methods: Optional fields that can attached to `Test Parameters`.


#### Test Parameter
When a product is tested, the result for all `Test Parameters` related to that product must be recorded.
Test Parameters has two result types: 

* Decimal: Indicates that the result of the test is a decimal value.
* Option: Indicates that the result of the test is a selection from a list of options.

When a Test Parameter is saved, the `Options` (If Applicable) and the `Normal Ranges` can be recorded.


#### Normal Range
A `Normal Range` is a range of values that is considered normal for a `Test Parameter`.
Depending on the `Result Type`, a Normal Range can be any decimal value between a minimum and maximum value, or a selection from a list of options.

!!! note
	A `Test Parameter` can have multiple `Normal Ranges`.  
	This is useful in case external factors affect the result of the test.  

	For example a Test could have different normal ranges during different seasons.