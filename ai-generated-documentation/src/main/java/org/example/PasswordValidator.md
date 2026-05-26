![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## PasswordValidator.java Documentation

**1. Overview:**

This Java program validates a user-provided password against a set of predefined criteria. The criteria include minimum length (7-13 characters), presence of at least one uppercase letter, one digit, and the "@" symbol.  The program prompts the user for a password, checks it against these rules, and provides feedback on whether the password meets the requirements or not.

**2. Package/module name:** org.example

**3. Class/file name:** PasswordValidator.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It initializes a `Scanner` to read user input, prompts the user for a password, and then calls the `validatePassword()` function to check its validity. Finally, it prints the validation result to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Creates a `Scanner` object to read input from the console.
       2. Prompts the user to enter their password using `System.out.println()`.
       3. Reads the entered password using `scanner.nextLine()` and stores it in the `password` variable.
       4. Calls the `validatePassword()` function, passing the `password` as an argument.
       5. Prints the result returned by `validatePassword()` to the console.

   - **`validatePassword(String password)`:** (Implicitly called within `main()`)
     - **Description:** This function checks if a given password meets the specified criteria. It determines the length, presence of uppercase letters, digits, and the "@" symbol. 
     - **Parameters:** `password`: The string representing the password to be validated.
     - **Return Values:** A boolean value (`true` if the password is valid, `false` otherwise).
     - **Important Logic:**
       1. Checks if the password length is within the allowed range (7-13 characters) using `password.length() >= 7 && password.length() <= 13`.
       2. Iterates through each character of the password:
         - If an uppercase letter is found, sets `hasUppercase` to `true`.
         - If a digit is found, sets `hasDigit` to `true`.
       3. Checks if all criteria are met (`hasValidLength`, `hasUppercase`, `hasAtSymbol`, and `hasDigit`). 
       4. Returns `true` if all criteria are satisfied, otherwise returns `false`.



**5. Key Variables and Data Structures:**

   - **`password` (String):** Stores the user-entered password string.
   - **`hasValidLength` (boolean):** Indicates whether the password length is within the allowed range.
   - **`hasUppercase` (boolean):** Indicates whether the password contains at least one uppercase letter.
   - **`hasAtSymbol` (boolean):** Indicates whether the password contains the "@" symbol.
   - **`hasDigit` (boolean):** Indicates whether the password contains at least one digit.

**6. Dependencies and Libraries:**

   - This program uses standard Java libraries:
     - `java.util.Scanner`: For reading user input from the console.



**7. Pseudo Code:**



```
// Class: PasswordValidator

// Method: main(String[] args)
  1. Create a Scanner object to read user input.
  2. Display a message prompting the user to enter their password.
  3. Read the entered password using the Scanner object and store it in the 'password' variable.
  4. Call the 'validatePassword()' function, passing the 'password' as an argument.
  5. Print the result returned by 'validatePassword()'.

// Method: validatePassword(String password)
  1. Check if the length of the password is between 7 and 13 characters (inclusive).
    - If not, return false.
  2. Initialize boolean variables to track the presence of uppercase letters, '@' symbol, and digits.
  3. Iterate through each character in the password:
    - If the character is uppercase, set 'hasUppercase' to true.
    - If the character is a digit, set 'hasDigit' to true.
    - If the character is '@', set 'hasAtSymbol' to true.
  4. Check if all criteria are met:
    - If 'hasValidLength', 'hasUppercase', 'hasAtSymbol', and 'hasDigit' are all true, return true.
    - Otherwise, return false.



```




