# PrimeNumbers-cli v0.3 - Java

This is a command line interface for working with prime numbers `{2, 3, 5, 7, ..., n}`

## Functionality

This version lets a user enter a number at the terminal which is then checked if it is a prime number of not and find the next prime number given an input.

## Main menu

    Select an option:
    1 - Check if number is prime
    2 - Find the next prime number after the input
    3 - Find all prime number given a range
    4 - Exit

### Check if a number is prime

    Enter a positive number to check if it's prime: 37 

    37 is a prime number.

### Find the next prime

    Enter a positive number to check to find the next prime: 10

    11 is the next prime number after 10.

If the given number is prime, it returns that number.

    Enter a positive number to check if it's prime: 11

    11 is a prime number.

### Find prime numbers in a range

    Find all prime numbers between two numbers
    Enter the first number:
    5
    Enter the second number:
    125
    The prime numbers from 5 to 125 are:
      5,    7,   11,   13,   17,   19,   23,   29,   31,   37,
     41,   43,   47,   53,   59,   61,   67,   71,   73,   79,
     83,   89,   97,  101,  103,  107,  109,  113.


## Running the App

To run the app in your local environment
1. Copy the following Commands
2. Open your terminal (Ctrl + Alt + T)
3. Paste (Ctrl + Shift + V)
4. Press Enter

```
    git clone git@github.com:bunny-thief/primeNumbers-cli.git
    cd primeNumbers-cli/src/main/java/
    javac org/primes/*.java
    java org.primes.Main
```
## Unit Tests

JUnit 5.10 tests have been written to ensure that each function returns the correct output.