# Postfix Calculator

Postfix Calculator is a simple command-line calculator that performs arithmetic operations using postfix notation. It supports basic arithmetic operations, exponentiation, square root, average calculation, and modulo operation.

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Interactive Mode](#interactive-mode)
  - [Command-Line Mode](#command-line-mode)
- [Supported Operations](#supported-operations)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++)
- Standard C++ Library

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/postfix-calculator.git
   cd postfix-calculator

2. Compile the source code:
g++ main.cpp Calc.cpp NumStack.cpp -o postfix-calculator

## Usage

### Interactive mode:
./postfix-calculator -p
Syötä numerot välilyönnillä ja operaatio lopussa:
(+, -, *, /, e(exp), r(sqrt), a(avg), %(modulo) tai x (vaihda kaksi ensimmäistä objektia pinossa)):
'esim 1. '2 1 x -' tai esim 2. '5 3 2 + '
'q' lopeta ohjelma.

### Command-Line Mode
Addition:
./postfix-calculator "2 3 +"
Output: 5

Exponentiation:
./postfix-calculator "2 3 e"

## Supported Operations
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Exponentiation (e)
Square root (r)
Average (a)
Modulo (%)
Swap top two elements (x)

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

Feel free to copy and paste this into your README file. Customize it based on your project's details and structure.

Tampere University of applied Sciences
@LeoSuzu 2024 / 02 / 08
leona.suzuki@tuni.fi


