# **Part1** Rational Numbers

## RationalNumber Class
1. RationalNumber(int numerator, int denominator): Constructor for the RationalNumber class. Initializes a rational number with the given numerator and denominator. It also simplifies the fraction by dividing both the numerator and denominator by their greatest common divisor (gcd).
2. gcd(int a, int b): Private helper method that calculates the greatest common divisor (gcd) of two integers using the Euclidean algorithm.
3. simplify(): Private method to simplify the rational number by dividing both the numerator and denominator by their gcd.
4. add(RationalNumber other): Adds another rational number to the current one and returns the result as a new RationalNumber object.
5. subtract(RationalNumber other): Subtracts another rational number from the current one and returns the result as a new RationalNumber object.
6. multiply(RationalNumber other): Multiplies the current rational number by another rational number and returns the result as a new RationalNumber object.
7. divide(RationalNumber other): Divides the current rational number by another rational number and returns the result as a new RationalNumber object.
8. toDouble(): Converts the rational number to a double-precision floating-point representation.
9. abs(): Returns the absolute value of the rational number as a new RationalNumber object.
10. toString(): Overrides the toString() method to represent the rational number as a string in the form "numerator/denominator".
## Test Class
1. main(String[] args): Entry point of the program. Allows users to input two rational numbers and performs arithmetic operations on them. It catches exceptions related to invalid input formats, division by zero, and arithmetic exceptions.

# **Part2** Factorial Calculation with Exception Handling

## FactorialException Class
1. FactorialException(int number): Constructor for the FactorialException class. Creates an exception object with a message indicating that the input number is invalid for factorial calculation.
2. toString(): Overrides the toString() method to provide a descriptive error message for the exception.
## Test Class
1. main(String[] args): Entry point of the program. Allows users to input a number and calculates its factorial. It handles exceptions related to invalid input formats and out-of-range numbers for factorial calculation.

# **Part3** Custom Exception for String Matching

## NOMATCHEXCP Class
1. NOMATCHEXCP(int lineNumber, String input): Constructor for the NOMATCHEXCP class. Creates an exception object with a message indicating that the input string does not match the expected value ("India").
## Test Class
1. main(String[] args): Entry point of the program. Allows users to input a string and checks if it matches the expected value ("India"). It throws a NOMATCHEXCP exception if the input string doesn't match and handles the exception by displaying a descriptive error message along with the line number where the exception occurred.











