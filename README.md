# Credit Card Validator

This project is a simple C++ program designed to validate credit card numbers using the Luhn Algorithm.

## Description

The Credit Card Validator program validates credit card numbers by performing the following steps:

1. **User Input**:
    - The program prompts the user to enter a credit card number or type 'exit' to quit.

2. **Input Validation**:
    - The program checks if the input consists only of numeric characters.
    - If the input is invalid, the user is prompted to enter the credit card number again.

3. **Luhn Algorithm**:
    - The program doubles every second digit from the right. If the result is a two-digit number, the digits are summed to produce a single digit.
    - The sum of these results is stored in `doubleEvenSum`.
    - The program adds every odd-placed digit (from the right) to `doubleEvenSum`.
    - Finally, the program checks if `doubleEvenSum` is a multiple of 10. If it is, the credit card number is valid. Otherwise, it is invalid.

## Usage

1. Compile and run the program.
2. Enter a credit card number to validate.
3. The program will output "Valid!" if the number is valid according to the Luhn Algorithm, and "Invalid!" if it is not.
4. Enter 'exit' to quit the program.

This program serves as an educational tool for understanding and implementing the Luhn Algorithm in C++.
