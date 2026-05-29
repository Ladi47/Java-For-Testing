![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## FizzBuzz.java Documentation

**1. Overview:**

This Java program implements the classic "FizzBuzz" challenge. It iterates through numbers from 1 to 20 and prints:

* "Fizz" if the number is divisible by 3,
* "Buzz" if the number is divisible by 5,
* "FizzBuzz" if the number is divisible by both 3 and 5,
* The number itself otherwise.

**2. Package/module name:** `org.example`

**3. Class/file name:** `FizzBuzz.java`

**4. Detailed Documentation:**

   - **Function/Method: `main(String[] args)`**
     - **Description:** This is the entry point of the program. It executes the FizzBuzz logic and prints the results to the console.
     - **Parameters:** 
        - `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None
     - **Important Logic:**
        - Iterates through numbers from 1 to 20 using a `for` loop.
        - For each number (`i`), it checks the following conditions:
           - If `i` is divisible by both 3 and 5, prints "FizzBuzz".
           - If `i` is divisible by 3 but not 5, prints "Fizz".
           - If `i` is divisible by 5 but not 3, prints "Buzz".
           - Otherwise, prints the value of `i`.

**5. Key Variables and Data Structures:**

   - **`i`**: An integer variable used as a counter in the `for` loop to iterate through numbers from 1 to 20.

**6. Assumptions and Dependencies:**

   - The code assumes that the input (numbers) are integers within the range of 1 to 20.
   - It relies on standard Java functionalities for outputting text to the console.

**7. Edge Cases and Error Handling:**

   - The code does not explicitly handle any edge cases or errors. It assumes valid input and performs its logic accordingly.


**8. Dependencies and Libraries:**

   - This program uses no external libraries. It relies solely on built-in Java functionalities.



**9. Pseudo Code:**

```
// Class: FizzBuzz

// Method: main(String[] args)
  1. Initialize a counter variable 'i' to 1.
  2. Loop from 'i' = 1 to 'i' = 20:
     - Check if 'i' is divisible by both 3 and 5:
        - If true, print "FizzBuzz".
     - Check if 'i' is divisible by 3 but not 5:
        - If true, print "Fizz".
     - Check if 'i' is divisible by 5 but not 3:
        - If true, print "Buzz".
     - Otherwise, print the value of 'i'.
     - Increment 'i' by 1.



```