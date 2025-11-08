# Simple Calculator

A simple command-line calculator built with Python.

## Features

- Addition
- Subtraction
- Multiplication
- Division

## Getting Started

### Prerequisites

- Python 3.11+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/simple-calculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd simple-calculator
   ```
3. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source .venv/bin/activate
     ```

## Usage

To use the calculator, you can import the functions from the `src.calculator` module.

```python
from src.calculator import add, subtract, multiply, divide

result = add(5, 3)
print(result)  # Output: 8
```

## Running the Tests

To run the tests, run the following command from the project root:

```bash
python -m unittest discover tests
```
