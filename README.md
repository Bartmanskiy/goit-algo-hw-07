## Description

This repository contains an object-oriented contact management assistant built with Python.
The project extends a basic address book with structured contact records, phone number management, birthday tracking, input validation, custom exceptions, and upcoming birthday notifications.

## Technologies

* Python
* Object-Oriented Programming (OOP)
* Classes and inheritance
* Custom exceptions
* `collections.UserDict`
* `datetime`
* Dictionaries and lists
* Decorators
* Data validation
* Command-line interface (CLI)

## Functionality

### Contact Management

The application provides a command-line assistant for managing contacts and supports:
* adding new contacts;
* updating existing contacts;
* adding and editing phone numbers;
* finding contact phone numbers;
* displaying all contacts;
* deleting and searching contact records.

### Birthday Management

The address book supports storing and managing contact birthdays.
The application allows users to:
* add a birthday to a contact;
* display a contact's birthday;
* find upcoming birthdays within a specified number of days;
* automatically move birthdays falling on weekends to the nearest working day.

### Data Validation

The application validates user input before storing it.
It validates:
* phone numbers using a 10-digit format;
* birthdays using the `DD.MM.YYYY` format;
* command arguments and required input parameters.

### Error Handling

A custom `input_error` decorator is used to handle common input errors and provide informative messages without terminating the application.
Custom exceptions are also defined for invalid phone-related operations.

### Object-Oriented Design

The application uses a structured class hierarchy:
* `Field` — base class for contact fields;
* `Name` — represents a contact name;
* `Phone` — validates and stores phone numbers;
* `Birthday` — validates and stores birthdays;
* `Record` — represents an individual contact;
* `AddressBook` — manages the collection of contact records.

## Links

GitHub: https://github.com/Bartmanskiy/goit-algo-hw-07
