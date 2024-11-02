# Parking
Overview
The parking spot management program simulates a parking lot system, allowing users to manage parking spots efficiently. The program provides functionalities to add vehicles to the parking lot, check for available parking spots, and remove vehicles when they leave.

Key Features
Parking Lot Initialization: The program initializes a parking lot with a specified number of parking spots.
Park Vehicle: Users can park a vehicle by providing its details (e.g., license plate number). The program checks for available spots and parks the vehicle if there is space.
Check Availability: Users can check how many parking spots are available in the lot at any time.
Remove Vehicle: Users can remove a vehicle from the parking lot by providing its license plate number, freeing up that spot.
Display Status: The program can display the current status of all parking spots, showing which spots are occupied and which are available.
Implementation Details
Data Structures:
A list or dictionary is used to represent the parking spots, where each spot can either be empty or contain vehicle information (like a license plate).
Functions:
initialize_parking_lot(size): Initializes the parking lot with the specified number of spots.
park_vehicle(license_plate): Parks a vehicle and updates the parking lot status.
check_availability(): Returns the number of available spots.
remove_vehicle(license_plate): Removes a vehicle from the parking lot based on its license plate.
display_status(): Prints the status of all parking spots.
