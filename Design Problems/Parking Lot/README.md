## Design a parking lot problem

### Design UML
![UML Diagram of Parking Lot](https://i.imgur.com/5SJqVLo.png)

### Solution

Vehicle
* size of vehicle (small, medium, large)
* status of vehicle (run or parked)
* *Sedan, SUV, Bus, Truck... extends Vehicle*

Slot
* size of slot
* status (available or not)

Lot
* hold slots in lot

Specs are below:

* The parking lot has multiple slots.
* The parking lot can park motorcycles, cars, and buses.
* The parking lot has small slots, compact slots, and large slots.
* A motorcycle can park in any slot.
* A car can park in either a single compact slot or a single large slot.
* A bus can park only in a single large slot.