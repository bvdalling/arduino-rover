# arduino-rover
A repo for an arduino rover designed for autonomous exploration and data collection using arduino controllers and sensors. Guidance and communications will require some additional research. 

## Goals

The main goal behind this project is to build something technical and fun outside of the world of web development where I currently exist. The project outlined will be something that aligns with my interest. However, I am no expert in this and this project will take quite some time to research, learn, and create. Therefore this project will likely take years without outside help. But if this is successful then this repo will contain schematics and component information for recreating, compiling the arduino source code, and docs for allowing others to create their own little rovers. 

* Semi-autonomous navigation
  - Should be capable of being assigned a navigation route and following the route with minor deviances. 
  - Should be able to avoid obstructions and attempt to regain correct course.
  - Should be capable of recieving precise movement controls from rover operator (used in circumstances where the rover can't decide for itself)
* Implements a module system where sensor equipment and software packages can be "plugged in"
  - Supports adding new sensors easily with a common API to talk to the storage / data controllers. 
  - Support tagging data from sensors for payload transmission (used for the application consuming the data to pull the data apart)
* Radio based communication
  - Capable of transmitting reasonable amount of data with error checking.
  - Capable of receiving new navigation information / transmitting current navigation information.
* GPS
  - This may not be feasible until later in the project.
    - Support navigation by GPS
    
## Tech

Arduino - Confirmed

## Contributors

I'm open to contributors on this project. This project will never be made private source and will server as a fun community project.
