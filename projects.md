---
layout: page
title: Projects
permalink: /projects/
---

#### DPRT: Dealer Plate Report & Tracking
DPRT is a platform for auto dealerships to manage their license plates and to record and get reports of test drives. It provides a central hub for keeping a record of all test drives, making it easier and more cost-effective for both dealerships and DMV/MVDs to audit test drive records.

The platform includes:
* The DPRT Dashboard, a web application where an office administrator can view a daily summary; get test drive reports for a date range; and manage users and dealer plates for the office
* Mobile applications to record and view active and past test drives

The mobile apps allow the dealer to record information about the test drive easily, simply by scanning barcodes from the driver's license and from the VIN barcode from the vehicle. The application provides real-time updates about active test drives, and what license plates are currently in use.

#### FACT: Food and ACtivity Tracker
##### CS 225: Next Generation Search Systems, Winter 2018
FACT is a mobile app for managing personal diet and exercise. It uses the Google Fit platform to log the user's physical activities (like walking, running, cycling, exercising, etc.), as well as the user's food intake. The user can set a fitness goal (gaining weight, losing weight, or maintaining weight). Based on the user's fitness goals, his/her activity levels, and food preferences, the app will recommend what food items to eat for each meal of the day (breakfast, lunch, dinner, as well as snacks).

The app is currently a prototype.

##### GitHub: [FACT](https://github.com/arashn/FACT)

#### Autonomous Campus Guide
##### CSE 181: Senior Design Project, Fall 2015 - Spring 2016
Designed an autonomous campus guide drone capable of navigating the user to a desired building on campus.  
The drone system has two components: mobile app and server. The mobile app is used by the user to request a drone and to specify the desired building, either on a map or by using the building code (e.g. DBH for Donald Bren Hall). The server is responsible for taking the user's request and sending the appropriate flight path to the drone. It takes the user's current location, the drone's current location, and the desired building, and uses Google Maps to determine a path for the drone to take. It then creates a flight path consisting of coordinates, or waypoints, for the drone to fly through, and sends the flight plan to the drone.

##### GitHub: [senior-project](https://github.com/arashn/senior-project)

#### 32-bit MIPS Processor
##### CSE 132L: Computer Architecture Lab, Winter 2016
Designed a 32-bit MIPS processor in VHDL. The processor is pipelined, allowing for multiple instructions in the pipeline in a single clock cycle. The processor design is broken into stages (fetch, decode, execute, mem, writeback), and the stages are integrated via registers at stage boundaries.  
As the team leader, I orchestrated project tasks among the team members, and oversaw the integration of the different components developed (controller, register file, 32-bit ALU, ROM, etc.)

##### Project source code: <a href="http://www.arashnabili.com/assets/cse132L_CART.zip">cse132L_CART.zip</a>
