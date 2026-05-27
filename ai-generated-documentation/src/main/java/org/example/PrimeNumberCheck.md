![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## PrimeNumberCheck.java Documentation

**1. Overview:**

This Java program determines whether a given integer is a prime number. A prime number is a whole number greater than 1 that has only two divisors: 1 and itself. The program utilizes a simple primality test algorithm to check for divisibility by numbers up to the square root of the input integer.

**2. Package/module name:** org.example

**3. Class/file name:** PrimeNumberCheck.java

**4. Detailed Documentation:**



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


