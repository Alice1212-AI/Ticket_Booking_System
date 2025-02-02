# Speed Bus Travel:

Speed Bus Travel is a Python-based console application for managing bus ticket bookings. It allows admin registration, admin login, passenger registration, ticket booking, and ticket display. The data is stored in CSV files for easy access and management.

# Features:

✅ Admin Registration & Login:

✅ Register a new admin with a username and password.

✅ Login with registered credentials.

✅ Passenger Registration & Ticket Booking:

✅ Enter passenger details such as name, number of passengers, departure location, destination, and journey date.

✅ Choose seat numbers from available options (up to two seats per booking).

✅ Select a bus type (AC or Non-AC) and calculate the fare.

✅ Store booking details in passengerData.csv.

# Ticket Display:

Retrieve and display a booked ticket using a unique booking ID.

# Installation:

Ensure Python is installed (Python 3 recommended).

Install necessary dependencies if required (CSV module is built-in).

# Run the program:

python main.py

# Usage:

1. Admin Registration & Login
When the program starts, select:
1: Register a new admin (credentials are saved in adminCredential.csv).
2: Login as an admin.
3. Passenger Registration
After admin login, choose:
1: Register a passenger.
Enter details (name, departure, destination, date, seat number, bus type, fare).
Information is stored in passengerData.csv.
5. Show Ticket
After login, choose:
2: Enter a booking ID to view the ticket.
File Structure
main.py - Entry point of the program.
admin.py - Handles admin registration and login.
passengerinfo.py - Manages passenger details and booking.
TicketShow.py - Displays booked tickets.
adminCredential.csv - Stores admin credentials.
passengerData.csv - Stores passenger booking data.
Future Enhancements
Implement a graphical user interface (GUI).
Add payment integration.
Enable real-time seat availability checks.
