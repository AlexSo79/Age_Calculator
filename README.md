# Age Calculator

This is a simple Python program that calculates the age of a person given their date of birth.

## How it works

The program defines a function called `age_calculator` that takes three parameters: `y`, `m`, and `d`, representing the year, month, and day of the person's date of birth, respectively.

The function imports the `datetime` module and uses the `datetime.date` class to create two objects: `today`, which represents the current date, and `dob`, which represents the date of birth.

The function then calculates the age by subtracting `dob` from `today` and dividing the result by 365.25 (the average number of days in a year, accounting for leap years). The function converts the result to an integer and prints it.

## Example

The program includes an example of calling the `age_calculator` function with the date of birth of March 30, 1979. The output is 44, which is the correct age as of December 11, 2023.
