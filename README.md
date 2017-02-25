# BookCab
Restful API for getting the best suitable cab for customers

Customers will be assigned a driver based on the following parameters.
  1.	Nearest Driver
  2.	Best rated driver
  3.	Number of seats available in the cab
  
The nearest route will be fetched using Google Maps API.

All the CAB and Customer details will be stored in a database. 

The following rest URL needs to called when the customer is booking a CAB

http://localhsot:8080/getRide/customerid/latitude/longituge/sharing=true|false

