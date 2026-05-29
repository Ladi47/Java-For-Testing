![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## MonthToSeason.java Documentation

**1. Overview:**

This Java program takes a month number as input from the user and determines the corresponding season. It uses a `switch` statement to map the month number to its respective season category (Winter, Spring, Summer, Autumn). If an invalid month number is entered, it displays an "Invalid month number" message.

**2. Package/module name:** org.example

**3. Class/file name:** MonthToSeason.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It prompts the user to enter a month number, reads the input, determines the season based on the entered month, and prints the result to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Creates a `Scanner` object to read user input from the console.
       2. Prints a message prompting the user to enter a month number.
       3. Reads the user's input using `scanner.nextInt()` and stores it in the `month` variable.
       4. Uses a `switch` statement to check the value of `month`:
         - Cases 12, 1, and 2: Print "Season: Winter".
         - Cases 3, 4, and 5: Print "Season: Spring".
         - Cases 6, 7, and 8: Print "Season: Summer".
         - Cases 9, 10, and 11: Print "Season: Autumn".
       5. If none of the cases match (i.e., an invalid month number is entered), print "Invalid month number".

**5. Key Variables and Data Structures:**

   - **`month` (int):** Stores the integer representing the month number entered by the user.


**6. Dependencies and Libraries:**

   - **java.util.Scanner:** This class is used for reading user input from the console. Equivalent libraries in other languages include:
     - Python: `input()` function
     - C++: `std::cin` object
     - JavaScript: `prompt()` function



**7. Pseudo Code:**

```
// Class: MonthToSeason

// Method: main(String[] args)
  1. Create a Scanner object to read user input from the console.
  2. Display a message prompting the user to enter a month number.
  3. Read the user's input as an integer and store it in the 'month' variable.
  4. Check the value of 'month':
     - If 'month' is 12, 1, or 2:
       - Print "Season: Winter"
     - If 'month' is 3, 4, or 5:
       - Print "Season: Spring"
     - If 'month' is 6, 7, or 8:
       - Print "Season: Summer"
     - If 'month' is 9, 10, or 11:
       - Print "Season: Autumn"
     - Otherwise (if 'month' is not within the valid range):
       - Print "Invalid month number"



```




