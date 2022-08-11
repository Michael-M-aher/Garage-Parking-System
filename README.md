
# Garage Parking System

Our Project for the Introduction to Software Engineering course
We applied all what we learned during the course in these project 
- Software Requirements Specifications (Functional and Non-Functional Requirements, Use Case Model, Use Case Tables)
- Software Design Specifications (Class diagrams, Sequence diagrams, Class - Sequence Usage Table) 
- Code (implemented with JAVA programming language) 
We applied the Object-Oriented-Programming concepts (Abstraction, polymorphism, interfaces, packaging, …) , SOLID Principles and Design patterns (Singelton, Strategy) in our program.


## Description:

A Parking Garage application that manages a parking space for a 
configurable maximum number of vehicles.  
Each parking space (slot) defined with a 
dimension (width and depth)

&nbsp;

The application handles the following functions:  
- Each vehicle is identified by a model name, unique identification number, Model 
year and vehicle dimensions (vehicle width and depth).  
- Park-in function that marks the arrival time of a vehicle if there is an available slot. The 
application shall capture such time automatically from the system.  
- During the park-in function the application picks a free slot based on the active slot configuration.  
&nbsp; 
  ### There are two configurations :  
    1. first come first served 
        i.e., the park-in function will use the first free slot available from the parking garage slots.   
    2. best-fit approach where you need to find the slot with the minimum dimension to hold the vehicle.  
&nbsp;
- Park-out function that marks the departure time of a vehicle from the garage. The 
application shall capture such time automatically from the system.  
- Calculate the parking fees during the park-out based on the time-of-stay with an hourly 
rate of 5 EGP.  
- Calculate the total income as well as the total number of vehicles that used the parking 
garage at any given point in time.  
- Display the available parking slots.  
---
## Authors  

- [@Michael-M-aher](https://www.github.com/Michael-M-aher)

## 📝 License  
Copyright © 2022  
This project is [MIT](https://github.com/Michael-M-aher/Garage-Parking-System/blob/main/LICENSE) licensed.
