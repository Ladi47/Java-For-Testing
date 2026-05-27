![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## FizzBuzz.java Documentation

**1. Overview:**

This Java program implements the classic "FizzBuzz" programming challenge. It iterates through numbers from 1 to 20 and prints:

* "Fizz" if the number is divisible by 3
* "Buzz" if the number is divisible by 5
* "FizzBuzz" if the number is divisible by both 3 and 5
* The number itself otherwise.

**2. Package/module name:** org.example

**3. Class/file name:** FizzBuzz.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It initializes a loop to iterate through numbers from 1 to 20 and calls conditional statements to determine the output for each number.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Uses a `for` loop to iterate from `i = 1` to `i <= 20`.
       - Inside the loop, it checks for divisibility by 3 and 5 using the modulo operator (`%`).
       - If divisible by both 3 and 5, prints "FizzBuzz".
       - If divisible by only 3, prints "Fizz".
       - If divisible by only 5, prints "Buzz".
       - Otherwise, prints the current value of `i`.

**5. Pseudo Code:**



**Dependencies and Libraries:**

This program does not rely on any external libraries. It utilizes built-in Java functionalities for looping, conditional statements, and printing output.


