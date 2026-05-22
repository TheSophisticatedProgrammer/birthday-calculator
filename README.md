# Birthday Countdown and Age Calculator

A command-line Python application that calculates your exact age and tracks the remaining days until your next birthday.

## Features

- **Precise Age Processing**: Factors in the current month and day to ensure an accurate age calculation.
- **Dynamic Year Tracking**: Automatically identifies if your birthday has passed this year and targets the next calendar year if necessary.
- **Days Countdown**: Outputs the exact number of days remaining until your next birthday.

## Prerequisites

- Python 3.x

## How to Run

1. Save the code to a file named `main.py`.
2. Open your terminal.
3. Execute the script:

## Usage Guide

1. Run the script in your terminal.
2. Provide your birth details when prompted:
   - **Birth day**: Enter as an integer (e.g., `15`).
   - **Birth month**: Enter as an integer (e.g., `8` for August).
   - **Birth year**: Enter as a four-digit integer (e.g., `1995`).
3. View your current age and the calculated days remaining until your next celebration.

## Technical Details

- **Module Dependency**: Uses `datetime.date` for real-time calendar tracking and date comparison.
- **Time Delta Calculation**: Employs object subtraction (`date - date`) to extract the exact integer count of remaining days.
