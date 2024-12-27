# Rapido Ride Booking

This is a simple ride booking application built using Python and Tkinter. The application allows users to book a ride by entering their name, pickup location, and drop location. The application then assigns the closest available rider and calculates the fare based on the distance.

## Features

- Book a ride by entering customer details.
- Calculate the distance and fare for the ride.
- Assign the closest available rider.
- Display ride details and progress.

## Requirements

- Python 3.x
- Tkinter (usually included with Python)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/rapido-ride-booking.git
    cd rapido-ride-booking
    ```

2. Install the required dependencies (if any):
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```sh
    python app.py
    ```

2. Fill in the customer name, pickup location, and drop location.
3. Click the "Book Ride" button to book a ride.
4. The application will display the ride details and show the progress of the ride.

## Code Overview

- : The main application file containing the GUI setup and ride booking logic.

### Classes and Functions

- : A class representing a ride booking.
  - : Initializes a new ride booking.
  - : Calculates a random distance for the ride.
  - : Calculates the fare based on the distance.

- : Finds the closest available rider from the list of riders.

- : Handles the ride booking process, including validating input, creating a ride, finding a rider, and displaying ride details.

## GUI Components

- : The main Tkinter window.
- : The title section of the GUI.
- : The input section for customer details.
- : Entry widget for customer name.
- : Dropdown menu for selecting pickup location.
- : Dropdown menu for selecting drop location.
- : Button to book a ride.
- : Label to display ride progress status.
- : Progress bar to show ride progress.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
