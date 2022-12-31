# Java_Workshop_Project
A Java project I made in college for calculating the charge of a taxi ride.

The program starts with showing the user a main menu. The user must login to one of the accounts in the program's existing database (represented by objects of the TaxiCustomer class).

After logging in, the user is presented with a user menu. The user can check his/her balance, deposit money in his/her account, book a ride or logout. Logging out takes the user back to the main menu.

Booking a ride takes the number of kilometres to travel as input and calculates the charge based on the following criteria:
- For the first 5 km, charge Rs. 25 per km
- For every km after that, charge Rs. 35 per km
Additionally, a surcharge is calculated based on the surcharge rate and added to the charge
