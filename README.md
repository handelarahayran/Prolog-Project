# Prolog-Project
# Prolog Date Manipulator

This project contains Prolog predicates to manipulate dates. Specifically, it provides utilities to add or subtract days from a given date. The date and the number of days are input as integers and the updated date is returned as a result.

## Project Structure

The project contains one Prolog file that defines a set of facts and predicates:
- The facts represent the months of a non-leap year and their respective number of days.
- The predicates are used to split a string into day and month, add days to a date, and subtract days from a date.

## Requirements

- SWI-Prolog

## Usage

1. Clone this repository to your local machine.
2. Load the Prolog file into your SWI-Prolog interpreter.
3. Use the predicates as required.

### Example

```prolog
?- split_string('2501', Month, Day).
Month = 25,
Day = 1.
