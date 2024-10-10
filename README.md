# Calculator Application with Plugin Architecture

This project is a Python-based calculator application that supports arithmetic operations through a plugin-based architecture. It allows users to perform various mathematical operations like addition, subtraction, multiplication, and division. The commands are implemented as separate plugins, and the application supports dynamic loading of these operations.

## Features

- **Dynamic Plugin Loading**: The application dynamically loads arithmetic operations (addition, subtraction, multiplication, division) as plugins.
- **Command Pattern**: Commands are handled using a structured command pattern.
- **Interactive Menu**: Users can select from available operations through a command-line interface.
- **Exception Handling**: Robust error handling for invalid inputs, including division by zero and non-numeric input.

## Installation

Install dependencies using the following command:

```bash
pip install -r requirements.txt

Testing

Run the tests using the following commands:
pytest
pytest --pylint
pyest --cov


Running the Application

Run the application using the following command:

python3 main.py

The application will present you with a menu of available commands:
Available commands:
1. calculator
2. exit
3. greet
4. menu

Select the calculator command to use arithmetic operations:
Calculator Operations:
1. AddCommand
2. SubtractCommand
3. MultiplyCommand
4. DivideCommand
