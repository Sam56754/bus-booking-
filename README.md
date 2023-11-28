# Sam@Travellers Bus Ticketing System

Welcome to the Sam@Travellers Bus Ticketing System! This system allows users to manage bus schedules, book seats, and review ticket information. Below, you'll find detailed information on how to use the system, its features, and how to contribute.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites
- [GCC](https://gcc.gnu.org/) (GNU Compiler Collection)
- [Code::Blocks](http://www.codeblocks.org/) or any other C IDE of your choice

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bus-ticketing-system.git
   cd bus-ticketing-system
Compile the code using GCC or your preferred compiler.

2. Run the executable:
    ```bash
    ./bus_ticketing_system 

## Features
### 1. User Authentication
Sign Up: Create a new account with a unique username and password.
Login: Authenticate users with their credentials.
### 2. Bus Schedule Management
Add a new bus schedule.
View existing bus schedules.
Delete bus schedules.
### 3. Booking System
Users can view available bus schedules and select seats for booking.
Seat availability is displayed through a seating chart.
Booking details, including customer information and fare, are stored securely.
The booking also allows multiple booking where a family can book up to a maximum of 20 seats which the seats will be under one of their names.
### 4. Booking history
users can view their booking history including the details of their past bookings with the bus seating arrangement being displayed.
### 5. Cancellation
Users can cancel their bookings if incidences occoured to them to demand cancellation of their ticket.
The cancelled seats are available for booking for other customers.
### 6. Ticket review
Users can review their tickets  details for a specific seat on a particular bus schedule. 
This helps to reprint the ticket a customer had if according to some incidences they happened to loose their ticket.
### 4. Account Modification
Change username.
Change password.

## Usage
### Sign Up or Login
Start the program and choose to sign up or log in.
sign up is for employees who currently do not have their accounts created.
if an account already exists, the sign up action will be invalid.
the account details are saved in a file where they can be externally accessed.

login function is executed when ption 2 is selected. the user has to be already signed up and have their accounts created. 
wrong username and password won't allow access to the program. 
### Main Menu
Choose from various options:
- Add a new bus schedule.
- View bus schedules.
- Delete a bus schedule.
- Book a bus.
- View booking history.
- Cancel a booking.
- Review ticketing.
- Modify account details.
- Exit.

## Bus Schedule Management
### Add a new bus schedule. 
The employees can add a bus schedule as desired. 
Details of the bus schedule include: 
Bus code- this will be determined by the travel company on the arrangenment of their buses, the default value is three digit numbers.
Bus route - also decided by the travel company where a bus will travel to any route desired.
Bus fare - this is the amount the compamny will charge according to the route a bus operates.
Time - this will show a time line from which a bus will depart and the estimated arrival time.This could help customers plan their schedules accordingly.
Date - this displays the bus travelling date. Will be printed on the receipt of every customer.
### View bus schedules.
This comes in handy when a customer needs to check the available buses and just know the prices.
The employees can just check and dictste to the customers of the available buses.
It shows a detailed view of the Bus code,bus fare,bus route, time and the date of travel of the bus.
### Delete a bus schedule.
This gives the employees an option to delete a bus schedule if the bus is already traveled or the bus is not functioning.
Once a schedule is deleted the seating arrangement is also deleted with it thus when a new bus is added a new chart will be added for it.

## Booking System
### Book a bus.
Selecting this option displays the available bus schedule with all the bus details.
After the customer choosing the bus schedule they need, the program displays the seating chart with a total of 56 seats(standard bus seats).
in the seating chart it show the names of the customers in the booked seats and the word 'empty' of the empty seats.
The customer is then asked for the number of seats they need to book. (a muximum of 20 seats is allowed to be booked at a time)  
After that the program request for the customer details including the name, ID number and the Phone number.(8 and 100 digits allowed on the ID number and phone number respectively)
The program then asks the user the seat number they want to book. Cannot select an already booked seat.
After the booking a receipt is generated displaying the number of seats booked, seat numbers booked, customer details and the bus details.
### View booking history.
This allows the employees to see how many seats in the bus are booked.  
It may also come in handy if a customer needs to know what seat they booked or how many seats they booked.  
It displays the bus schedules where the employee chooses the one they need to check the booked seats of.
Once seleccted a seating chart is displayed showing booked and unbooked for each of the buses.
### Cancel booking.
This option displays the bus schedules where you choose a schedule containing the seat you want to cancel.  
After choosing a schedule, the seating chart is displyed (1-56) an already booked is to be selected and cancelled if desired.  
an Empty seat cannot be cancelled.
### Review ticketing
This is usefule if a customer genuinely lost their ticket.  
Once selected the bus schedule is displayed. You choose the bus with the seat ticket you want to review on customer's demand.
The seating chart of the bus is displayed where you choose the specific seat you need to review its ticket. An almost similar ticker to the one before is displayed with the customer details and the bus details. 
## Account Modification
- Change your username -This provides the user with the option to change their current user name. you will be prompted to enter your previous username. If user name is not found you will get an invalid error, if found it will succesfully change it to the new user name.
- Change your password -This provides the user with the option to change their current password. you will be prompted to enter your new password and it will change it to the new password

## Contributing
We welcome contributions to improve this project. If you'd like to contribute, please follow these steps:  
Fork the repository.  
Create a new branch: `git checkout -b feature/your-feature.`  
Commit your changes: `git commit -m 'Add some feature'.`  
Push to the branch: `git push origin feature/your-feature.`  
Submit a pull request.  

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
