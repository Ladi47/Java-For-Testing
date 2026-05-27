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
     - **Description:** This is the entry point of the program. It prompts the user for input, calculates the sum of numbers, and prints the result.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Creates a `Scanner` object to read input from the console (`System.in`).
       - Reads an integer value from the user using `sc.nextInt()` and stores it in the variable `n`.
       - Initializes an integer variable `sum` to 0.
       - Uses a `for` loop to iterate from 1 to `n` (inclusive). In each iteration, it adds the current loop counter (`i`) to the `sum` variable.
       - After the loop completes, prints the calculated `sum` using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - **`n`**: An integer variable holding the user-provided input number.
   - **`sum`**: An integer variable that accumulates the sum of numbers from 1 to `n`.

**6. Dependencies and Libraries:**

   - This program relies on the standard Java library `java.util.Scanner` for reading user input.


**7. Pseudo Code:**

```
// Class: SumAllNumbers





```




