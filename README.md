# Leap Year and Days-in-Month Checker (Python)

## Overview
This project includes two Python functions:

1. `is_year_leap(year)`
Checks whether a given year is a leap year.

2. `days_in_month(year, month)`
Returns the number of days in a given month for a given year, including leap-year handling for February.

The script also includes a small built-in test loop to validate sample inputs.

## Leap Year Rules
A year is a leap year if:

1. It is divisible by 400, or
2. It is divisible by 4 and not divisible by 100

Otherwise, it is not a leap year.

## Project File
- `leap_Year.py`: function implementation and test code.

## How to Run
From the project folder, run:

```bash
python leap_Year.py
```

## Expected Output
```text
1900 2 ->OK
2000 2 ->OK
2016 1 ->OK
1987 11 ->OK
```

## Function Signatures
```python
def is_year_leap(year):
	...

def days_in_month(year, month):
	...
```

## Notes
- `month` should be between 1 and 12.
- If `month` is outside that range, `days_in_month` returns `None`.
- Included tests are basic sanity checks and can be expanded.

# Leap_Year_And_Days_In_Month_Checker
