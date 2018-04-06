---
layout: page
title: Projects
permalink: /projects/
---

#### Senior Design Project
Designed an autonomous campus guide drone capable of navigating the user to a desired building on campus.  
The drone system has two components: mobile app and server. The mobile app is used by the user to request a drone and to specify the desired building, either on a map or by using the building code (e.g. DBH for Donald Bren Hall). The server is responsible for taking the user's request and sending the appropriate flight path to the drone. It takes the user's current location, the drone's current location, and the desired building, and uses Google Maps to determine a path for the drone to take. It then creates a flight path consisting of coordinates, or waypoints, for the drone to fly through, and sends the flight plan to the drone.

###### GitHub: [senior-project](https://github.com/arashn/senior-project)
