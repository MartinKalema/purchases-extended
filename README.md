# Purchases-Extended

Odoo comes with a number of default applications that include 'Purchases Applications'. The RFQ module however, has some missing functionalities that need to be implemented. I will add a one-to-many relationship between an RFQ and Vendors. Create a customization in the system such that one RFQ could be assigned to several vendors at the model-level. Additionally, I will extend these features to the front-end interfaces such that it's possible for the end-user to perform such actions. In summary, i will 
-  Add the ability to assign RFQ to several vendors. Not that this implementation will require you to implement a new module that inherits from an existing module.
-  Add process for receiving bids from suppliers against the RFQ that was issued (one-to-many relation between and RFQ and Bids)
-  Add process for selecting the winning bidder and assigning them a Purchase Order.
-  Implement a purchase-request module that is used by employees to send purchase requests to the Procurement department. Note that the procurement department would use this request to prepare an RFQ specified in item 1 above.
