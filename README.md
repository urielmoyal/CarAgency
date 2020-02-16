# VehicleAgency

### Introduction
Vehicle agency management **GUI** program that holds a database of various
vehicles that it wants to sell. Implementation with **Thread control** such as
*thread pool, semaphore locks, synchronization* and more.

### Features
+ **Operations:**
  * Add new Vehices - adding new vehicles to vehicles agency.
  * Buy vehicle - buying vehicle from the agency.
  * Test drive - take a vehicles from the agency to a test drive.
  * Change flag - change vehicle flage (only for sea-vehicles).
+ **Vehicles:**
  * Jeep
  * Frigate
  * Bicycle
  * Spy glider
  * Toy glider
  * Cruise ship
  * Amphibious
  * Elctric bicycle
  * Hybrid aircraft
+ **System operations:**
  * Miles reset - reset vehicle miles after test drive.
  * Show vehicles agency - show all vehicles exists in the agency.
  * Save current state - save current state of vehicles agency, miles and changes.
  * Previous state - previous state go back (of 3 last states saves).
  
  ### Design Patterns:
|Design Pattern  | Use |
| :-------------: | ------------- |
| **Abstract factory** | Using to producing new vehicles and to make sure that the system is expandable. |
| **Thread pool**| Used to limit the number of test drive windows. |
| **Singlethon**  | Implementing in "main menu" window to limit the number of windows.  |
| **Deligator**  | Used to avoid multiple inheritance.   |
| **Decorator** | Used to adding a vehicle color and a vehicle status in run-time. |
| **Memento** | Used to saving 3 state and to return to the state. |
| **Observer**| Used to calculating the total mileage of all vehicles test drive. |

### Demonstration
 > Video Demonstration
![Video Demonstration](Demonstration.gif)
