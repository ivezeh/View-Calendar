# Calendar Display Program 📅

This Python script allows you to display the calendar for a specific month and year. The script uses Python's built-in `calendar` module to generate and print the calendar.

## Features

- **Display Calendar**: Shows the full calendar of a specified month and year.
- **Customizable Input**: The script can be easily modified to take user input for the year and month.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

No installation is required. You can simply run the script with Python.

### Usage

The script currently displays the calendar for November 2014 by default. You can modify the `yy` and `mm` variables in the script to change the year and month, or uncomment the input lines to allow user input.

```python
# Program to display calendar of the given month and year

# importing calendar module
import calendar

yy = 2014  # year
mm = 11    # month

# To take month and year input from the user
# yy = int(input("Enter year: "))
# mm = int(input("Enter month: "))

# display the calendar
print(calendar.month(yy, mm))
```

# Example: Display the calendar for August 2023
yy = 2023
mm = 8
print(calendar.month(yy, mm))
