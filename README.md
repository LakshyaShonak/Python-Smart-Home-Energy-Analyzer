# Smart Home Energy Analyzer

## Project Overview

Smart Home Energy Analyzer is a Python-based web application that
estimates household electricity consumption and monthly electricity
costs. Users can enter appliance details such as power rating, quantity,
daily usage hours, and electricity rate. The system calculates energy
consumption, estimates the monthly bill, identifies the
highest-consuming appliance, and provides a simple energy-saving
suggestion.

## Technologies Used

-   Python
-   PyScript
-   HTML
-   CSS
-   Web Browser

## Features

-   Add household appliances
-   Enter power rating, quantity, and daily usage
-   Calculate daily electricity consumption
-   Calculate estimated monthly consumption
-   Estimate monthly electricity cost
-   Identify the highest-consuming appliance
-   Display appliance-wise consumption
-   Show an energy status and saving suggestion
-   Clear all appliance records

## Calculation

### Daily Units

`Daily Units = (Power × Quantity × Hours Per Day) / 1000`

### Monthly Units

`Monthly Units = Daily Units × 30`

### Estimated Monthly Bill

`Estimated Bill = Monthly Units × Electricity Rate`

## Example

For an air conditioner rated at 1500 W, used for 6 hours per day:

-   Daily consumption = 9 units
-   Monthly consumption = 270 units
-   At ₹8 per unit, estimated monthly cost = ₹2,160

## How to Run

1.  Download the project HTML file.
2.  Make sure you have an internet connection so the PyScript runtime
    can load.
3.  Open the HTML file in a modern web browser.
4.  Enter appliance information in the input section.
5.  Click **Add Appliance**.
6.  Review the calculated consumption, estimated bill, highest consumer,
    and energy-saving suggestion.

## Project Structure

The project is implemented as a single HTML file containing:

-   HTML for the user interface
-   CSS for styling
-   PyScript for running Python
-   Python logic for calculations and analysis

## Python Concepts Demonstrated

-   Variables
-   Functions
-   Lists
-   Dictionaries
-   Loops
-   Conditional statements
-   Arithmetic operations
-   Input validation
-   Basic data analysis

## Limitations

-   Uses a single electricity rate instead of real tariff slabs.
-   Assumes a fixed 30-day month.
-   Actual appliance consumption may differ from rated power.
-   Does not connect to a smart meter or electricity provider.
-   Internet access is normally required to load PyScript.

## Future Scope

-   Add real electricity tariff slabs
-   Store and compare monthly calculations
-   Add more charts and reports
-   Allow editing and deleting appliances
-   Generate downloadable electricity reports
-   Add database storage and user profiles
-   Integrate smart-meter or IoT data
-   Provide more detailed energy-saving recommendations

## Authors

**Lakshya Shonak** --- 26MCC20059

**Chandigarh University**\
University Institute of Computing\
2026
