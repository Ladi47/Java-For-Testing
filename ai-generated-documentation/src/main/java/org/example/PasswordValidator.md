![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## PasswordValidator.java Documentation

**1. Overview:**

This Java program validates a user-provided password against a set of predefined criteria. It checks if the password meets the following requirements:

* Length: Between 7 and 13 characters inclusive.
* Uppercase Letter: Contains at least one uppercase letter.
* "@" Symbol: Contains exactly one "@" symbol.
* Digit: Contains at least one digit.

The program prompts the user to enter a password, then evaluates it based on these criteria and prints an appropriate message indicating whether the password is valid or not.

**2. Package/module name:** `org.example`

**3. Class/file name:** `PasswordValidator.java`

**4. Detailed Documentation:**

   - **Function/Method: `main(String[] args)`**
     - **Description:** This is the entry point of the program. It prompts the user for a password, validates it against the defined criteria, and prints the result.
     - **Parameters:** 
        - `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None
     - **Important Logic:**
        - Creates a `Scanner` object to read user input from the console.
        - Prompts the user to enter their password using `System.out.println()`.
        - Reads the entered password using `scanner.nextLine()` and stores it in the `password` variable.
        - Checks if the password meets each criterion: length, uppercase letter, "@" symbol, and digit.
        - Prints an appropriate message based on the validation results.

   - **Function/Method:** (None) - The code only contains a single `main` method.


**5. Key Variables and Data Structures:**

   - **`password`**: A string variable holding the user's entered password.
   - **`hasValidLength`**: A boolean variable indicating whether the password length is within the allowed range (7 to 13 characters).
   - **`hasUppercase`**: A boolean variable indicating whether the password contains at least one uppercase letter.
   - **`hasAtSymbol`**: A boolean variable indicating whether the password contains exactly one "@" symbol.
   - **`hasDigit`**: A boolean variable indicating whether the password contains at least one digit.

**6. Assumptions and Dependencies:**

   - The code assumes that the user will enter a valid string as input. It does not handle cases where the input might be null or contain invalid characters.
   - It relies on the standard Java libraries for input/output (`Scanner` class), string manipulation (`String` class), and character checking (`Character.isUpperCase()` and `Character.isDigit()`).

**7. Edge Cases and Error Handling:**

   - The code does not explicitly handle cases where the user enters an invalid input (e.g., non-string characters, empty input).
   - It assumes that the user will enter a password within the specified length range.


**8. Dependencies and Libraries:**

   - **Java:** This program uses the built-in Java `Scanner` class for reading user input, the `String` class for string manipulation, and methods like `Character.isUpperCase()` and `Character.isDigit()` for character checking.



**9. Pseudo Code:**

```
// Class: PasswordValidator

// Method: main(String[] args)
  1. Create a Scanner object to read user input from the console.
  2. Prompt the user to enter their password using "Validate your password: ".
  3. Read the entered password from the console and store it in the `password` variable.
  4. Initialize boolean variables:
     - `hasValidLength`: Set to false initially.
     - `hasUppercase`: Set to false initially.
     - `hasAtSymbol`: Set to false initially.
     - `hasDigit`: Set to false initially.
  5. Check if the password length is between 7 and 13 characters (inclusive):
     - If true, set `hasValidLength` to true.
  6. Iterate through each character in the password:
     - If the character is uppercase, set `hasUppercase` to true.
     - If the character is a digit, set `hasDigit` to true.
     - If the character is "@", set `hasAtSymbol` to true (only one occurrence allowed).
  7. Check if all criteria are met:
     - If `hasValidLength`, `hasUppercase`, `hasAtSymbol`, and `hasDigit` are all true, print "Password match the requirements".
     - Otherwise, print an appropriate error message based on which criterion is not met:
       - Password must be 7–13 characters long.
       - Password must contain at least one uppercase letter.
       - Password must contain '@' symbol.
       - Password must contain at least one number.



```