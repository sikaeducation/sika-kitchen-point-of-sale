1. As a customer, I need to pay the restaurant so I can settle my bill

* Given a bill and an order, a user can input a gratuity
* The system displays the grand total, which is the bill amount plus the gratuity
* A user can charge a Visa, Mastercard, or Discover card a grand total between $1 and $1000

2. As a server, I need to generate a bill for the customer so they know how much to pay

* Given an order, a user can press a button to generate a bill
* A user can print a bill
* The bill includes a list of items ordered and their prices
* The bill includes a total of all the items
* The bill includes the local sales tax
* The bill includes a total of all the items plus the sales tax
* The bill includes an option for manually writing a gratuity with a pen
* The bill includes an option for manually writing the grand total with a pen
* The bill an area for signing a bill with a pen

3. As a server, I need to generate a receipt for the customer so they know their bill is settled

* When a credit card charge is successfully processed, it displays a receipt
* When a credit card charge is unsuccessfully processed, it displays a reason
* A user can press a button to print a receipt
* The receipt includes a list of items ordered and their prices
* The receipt includes a total of all the items
* The receipt includes the local sales tax
* The receipt includes a total of all the items plus the sales tax
* The receipt includes the amount of the gratuity
* The receipt includes the grand total

2. As a kitchen worker, I need to see the existing orders so I can make decisions about what to cook

* A user can see a list of any open orders in the system
* The orders are listed in the order they were entered
* The orders display how long it's been since they were entered

3. As a server, I need to see the existing orders so I can estimate the kitchen's wait time

* A user can see a list of any open orders in the system
* The orders are listed in the order they were entered
* The orders display how long it's been since they were entered

4. As a server, I need to take customer orders so I can communicate to the kitchen about what to cook

* A user can add any menu item to an order
* A user can indicate that an order is ready for the kitchen
* A user can continue adding menu items after an order can been sent to the kitchen
* A user can remove an item from an order
* A user can cancel an order

5. As a kitchen worker, I need to indicate that an order is fulfilled so that I only cook it once

* A user can press a button to mark an order as fulfilled
* A user can see which orders have been fulfilled

I chose the payment story first, because processing payment adds the most value overall to the restaurant; if a restaurant can do everything but accept payment, it can't make money. The bill is necessary for the customer to know how much to pay, and the receipt is necessary proof. The three stories need to be complete for a customer to satisfactorily pay the restaurant.

I chose the ability to see existing orders as the next most valuable story because if a user can't see that an order is in the system, it doesn't matter that they can input or fulfill it. The kitchen worker's story is identical to the server's story, but indicates different needs that may require different functionality. The kitchen worker's is prioritized higher because it directly adds value, while the server's story only indirectly adds value. Once the orders can be seen, servers need a way to add orders to make the system dynamic. This is more important than indicating than order is fulfilled because it increases the overall throughput of the system.
