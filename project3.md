[Back to Portfolio](./)

Calendar
===============

-   **Class: CSCI 325 - Object-Oriented Programming** 
-   **Grade:** 
-   **Language(s): Java** 
-   **Source Code Repository:** [CSCI 325 - Object-Oriented Programming](https://github.com/RicoNoSuave/CSCI325-Object_Oriented_Programming)  
    (Please [email me](mailto:Ricardo.E.Harris@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This is a Personal Calendar project built in Java to demonstrate a mastery of principles of Object Oriented Programming. The project is built to allow users to create, read, update, and delete time-based appointments and day-based events, including names, dates, and descriptions, as well as start and end times for time-based appointments. Furthermore, time-based appointments are validated against existing appointments to prevent overlap. This program is built as a command-line interface.

## How to compile and run the program

To compile and run the program, make sure you have the Java Development Kit installed on your device, then run the following:

```bash
cd ./Calendar;
javac *;
java CLI;
```

## UI Design

When running the program, you will begin at the top menu of the calendar (see Fig 1). From the menu, you can create an event (see Fig 2) or an appointment (see Fig 3). The menus for each are quite similar to represent the relationship between events and appointments: An appointment is any event with a start and end time. For instance, your birthday or a holiday is an event, whereas a party to celebrate these occasions would be an appointment. To create these objects, you need a calendar to save the event to, a title for the object, a date, a description, and a location, plus a start and end time in the case of an appointment (see Fig 2 and 3). After creating an event or appointment, you can search for a list of objects by name (see Fig 4) or by date (see Fig 5). After finding an event or appointment, you are able to edit or delete said object (see Fig 5). Lastly, when finished you can quit (see Fig 6).

![screenshot](/images/OOP_Calendar/Menu.jpg)  
Fig 1. The launch menu.

![screenshot](/images/OOP_Calendar/Create_Event.jpg)  
Fig 2. Menu to create an appointment.

![screenshot](/images/OOP_Calendar/Create_Appointment.jpg)  
Fig 3. Menu to create an event.

![screenshot](/images/OOP_Calendar/Find_Appointment.jpg)  
Fig 4. Output when searching by title.

![screenshot](/images/OOP_Calendar/Access_Edit_Appointment.jpg)  
Fig 5. Method to find and edit appointments and events.

![screenshot](/images/OOP_Calendar/Quit.jpg)  
Fig 6. Feedback when quitting.

## 3. Additional Considerations

If you would rather use a pre-existing Java Development Environment, copy the files of this project to a new directory to run.

[Back to Portfolio](./)
