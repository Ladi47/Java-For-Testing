![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## SumAllNumbers.java Documentation

**1. Overview:**

This Java program calculates the sum of all integers from 1 to a user-specified number. It takes an integer input from the user, iterates through the numbers from 1 to the input value, and accumulates their sum. Finally, it prints the calculated sum to the console.

**2. Package/module name:** org.example

**3. Class/file name:** SumAllNumbers.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It reads an integer input from the user, calculates the sum of numbers from 1 to the input value, and prints the result.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Creates a `Scanner` object to read user input from the console (`System.in`).
       2. Reads an integer value from the user using `sc.nextInt()` and stores it in the variable `n`.
       3. Initializes an integer variable `sum` to 0.
       4. Uses a `for` loop to iterate through numbers from 1 to `n`:
         - In each iteration, adds the current value of `i` to the `sum` variable.
       5. Prints the final value of `sum` using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - **`n` (int):** Stores the integer input from the user, representing the upper limit for summing numbers.
   - **`sum` (int):** Accumulates the sum of integers from 1 to `n`.


**6. Dependencies and Libraries:**

   - This program uses the standard Java library:
     - `java.util.Scanner`: For reading user input from the console.



**7. Pseudo Code:**

```
// Class: SumAllNumbers

// Method: main()
  1. Create a Scanner object to read input from the console.
  2. Read an integer value from the user and store it in variable "n".
  3. Initialize a variable "sum" to 0.
  4. Iterate through numbers from 1 to "n":
    - Add the current number to the "sum" variable.
  5. Print the final value of "sum" to the console.



```




