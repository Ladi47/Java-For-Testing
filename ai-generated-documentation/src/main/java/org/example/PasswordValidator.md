![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## PasswordValidator.java Documentation

**1. Overview:**

Sorts an array of integers.

**2. Package/module name:** org.example

**3. Class/file name:** PasswordValidator.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It prompts the user to enter a password, reads the input, and then calls various functions to validate it against the defined criteria. Finally, it prints a message indicating whether the password is valid or not.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Creates a `Scanner` object to read user input from the console.
       - Prompts the user to enter their password using `System.out.println()`.
       - Reads the entered password using `scanner.nextLine()` and stores it in the `password` variable.
       - Calls functions `hasValidLength()`, `hasUppercase()`, `hasAtSymbol()`, and `hasDigit()` to check individual criteria.
       - Based on the results of these checks, prints a message indicating whether the password is valid or not using `System.out.println()`.

   - **`hasValidLength(String password)`:**
     - **Description:** This function checks if the length of the password is within the allowed range (7 to 13 characters inclusive).
     - **Parameters:** `password`: The input string to be checked for length validity.
     - **Return Values:** Returns `true` if the password length is valid, `false` otherwise.
     - **Important Logic:**
       - Uses a conditional statement (`&&`) to check if the length of the `password` is greater than or equal to 7 and less than or equal to 13.

   - **`hasUppercase(String password)`:**
     - **Description:** This function checks if the password contains at least one uppercase letter.
     - **Parameters:** `password`: The input string to be checked for uppercase letters.
     - **Return Values:** Returns `true` if the password contains at least one uppercase letter, `false` otherwise.
     - **Important Logic:**
       - Iterates through each character of the `password` using a `for` loop.
       - For each character, it uses `Character.isUpperCase()` to check if it's an uppercase letter.
       - If an uppercase letter is found, sets the `hasUppercase` flag to `true` and breaks out of the loop.

   - **`hasAtSymbol(String password)`:**
     - **Description:** This function checks if the password contains the "@" symbol.
     - **Parameters:** `password`: The input string to be checked for the "@" symbol.
     - **Return Values:** Returns `true` if the password contains the "@" symbol, `false` otherwise.
     - **Important Logic:**
       - Uses the `contains()` method of the `String` class to check if the `password` string contains the character "@".

   - **`hasDigit(String password)`:**
     - **Description:** This function checks if the password contains at least one digit.
     - **Parameters:** `password`: The input string to be checked for digits.
     - **Return Values:** Returns `true` if the password contains at least one digit, `false` otherwise.
     - **Important Logic:**
       - Iterates through each character of the `password` using a `for` loop.
       - For each character, it uses `Character.isDigit()` to check if it's a digit.
       - If a digit is found, sets the `hasDigit` flag to `true` and breaks out of the loop.



**5. Pseudo Code:**

```
// Class: PasswordValidator

// Method: main(String[] args)
  1. Create a Scanner object to read user input from the console.
  2. Prompt the user to enter their password using "Validate your password: ".
  3. Read the entered password using scanner.nextLine() and store it in the 'password' variable.
  4. Check if the password has a valid length (7-13 characters) using 'hasValidLength()'.
  5. Check if the password contains at least one uppercase letter using 'hasUppercase()'.
  6. Check if the password contains the "@" symbol using 'hasAtSymbol()'.
  7. Check if the password contains at least one digit using 'hasDigit()'.
  8. Based on the results of the checks, print a message indicating whether the password is valid or not:
      - If any check fails, print an error message specifying the missing requirement.
      - If all checks pass, print "Password match the requirements".



```

**6. Dependencies and Libraries:**

   - **java.util.Scanner:** Used for reading user input from the console. This is a standard Java library.


