# Rocket-Elevators-Java-Controller
Source Code file:  Commercial_Controller.java 
You can run the Commercial_Controller.java source file code at the terminal of your preference. Before you need to compile the file by typing: **javac Residential_Controller.java**

Then it will generate all new java class files including **Residential_Controller.class** and now you can run the program by typing: **java Residential_Controller

SUMMARY:
1- class Battery
    a- Access: public, class name: Battery, instance variables, constructor declaration of class.
    b= Method tostring 
    c- Methods to create a list: createColumnsList, createListsInsideColumns
    d- Methods for logic: calculateamountOfFloorsPerColumn, etColumnValues, initializeBasementColumnFloors, initializeMultiColumnFloors, initializeUniqueColumnFloors
    
    
2- class Column
    a- Access: public, class name: Column, instance variables, constructor declaration of class.
    b= Method tostring 
    c- Methods to create a list: createElevatorsList, createButtonsUpList, createButtonsDownList
    d- Methods for logic: findElevator, findNearestElevator, manageButtonStatusOn
    e. Entry method: requestElevator
3- class Elevator
    a- Access: public, class name: Column, instance variables, constructor declaration of class.
    b= Method tostring 
    c- Methods to create a list: createFloorDoorsList, createDisplaysList, createfloorRequestButtonsList
    d- Methods for logic: moveElevator, moveUp, moveDown, manageButtonStatusOff, updateDisplays, openDoors, closeDoors, checkWeight, checkObstruction, addFloorTofloorRequestList, deleteFloorFromList
    e. Entry method: requestFloor
4- class Door
5- class Display
6- ENUMS: special class represents a group of constants 


