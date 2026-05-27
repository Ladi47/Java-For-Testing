![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## PrimeNumberCheck.java Documentation

**1. Overview:**

This Java program determines whether a given integer is a prime number. A prime number is a whole number greater than 1 that has only two divisors: 1 and itself. The program utilizes a simple primality test algorithm to check for divisibility by numbers up to the square root of the input integer.

**2. Package/module name:** org.example

**3. Class/file name:** PrimeNumberCheck.java

**4. Detailed Documentation:**

   - **`isPrime(int n)`:**
     - **Description:** This function checks if a given integer `n` is a prime number.
     - **Parameters:** `n`: The integer to be checked for primality.
     - **Return Values:** Returns `true` if `n` is a prime number, `false` otherwise.
     - **Important Logic:**
       - Handles the base cases: If `n` is less than or equal to 1, it returns `false` as 1 and numbers less than 1 are not prime.
       - Iterates from 2 up to the square root of `n`. For each number `i` in this range, it checks if `n` is divisible by `i`. If it finds a divisor, it immediately returns `false` because `n` is not prime.
       - If the loop completes without finding any divisors, it means `n` is only divisible by 1 and itself, hence it's a prime number, and the function returns `true`.

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It calls the `isPrime()` function to check if the number 11 is prime and prints the result.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Calls `isPrime(11)` to check if 11 is a prime number.
       - Prints the result returned by `isPrime(11)` using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - None


**6. Dependencies and Libraries:**

   - **java.lang.Math:** Used for the `sqrt()` method to calculate the square root of a number. This is a standard Java library.



**7. Pseudo Code:**

```
// Class: PrimeNumberCheck

// Method: isPrime(n)
  1. If n <= 1, return false.
  2. For i = 2 to the square root of n:
    - If n % i == 0, return false.
  3. Return true.

// Method: main()
  1. Call isPrime(11).
  2. Print the result returned by isPrime(11).



```


