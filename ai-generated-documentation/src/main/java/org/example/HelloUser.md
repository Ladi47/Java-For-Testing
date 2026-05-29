![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## HelloUser.java Documentation

**1. Overview:**

This Java program greets the user by name. It prompts the user to enter their name, reads the input, and then displays a personalized greeting message using the provided name. 

**2. Package/module name:** org.example

**3. Class/file name:** HelloUser.java

**4. Detailed Documentation:**

   - **`helloUser(String name)`:**
     - **Description:** This function takes a user's name as input and returns a greeting message formatted as "Hello [name]!".
     - **Parameters:** `name`: A string representing the user's name.
     - **Return Values:** A string containing the personalized greeting message.
     - **Important Logic:** Concatenates the strings "Hello ", the provided `name`, and "!" to create the greeting message.

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It initializes a `Scanner` object to read user input, prompts the user for their name, reads the input, calls the `helloUser()` function to generate the greeting, and finally prints the greeting message to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Creates a `Scanner` object to read input from the standard input stream (`System.in`).
       - Prints a prompt message asking the user to enter their name.
       - Reads the user's input using `scanner.nextLine()` and stores it in the `name` variable.
       - Calls the `helloUser()` function, passing the `name` as an argument, and stores the returned greeting message.
       - Prints the greeting message to the console using `System.out.println()`.
       - Closes the `Scanner` object to release resources.

**5. Key Variables and Data Structures:**

   - **`name` (String):** Stores the user's name entered as input.


**6. Dependencies and Libraries:**

   - **java.util.Scanner:** This class is used for reading user input from the console. Equivalent libraries in other languages include:
     - Python: `input()` function
     - C++: `std::cin` object
     - JavaScript: `prompt()` function


**7. Pseudo Code:**

```
// Class: HelloUser

// Method: main(String[] args)
  1. Create a Scanner object to read user input from the console.
  2. Print a message prompting the user to enter their name.
  3. Read the user's input using the Scanner object and store it in the 'name' variable.
  4. Call the 'helloUser' function, passing the 'name' as an argument.
  5. Store the returned greeting message from the 'helloUser' function.
  6. Print the greeting message to the console.
  7. Close the Scanner object to release resources.

// Method: helloUser(String name)
  1. Concatenate the strings "Hello ", the provided 'name', and "!" to create the greeting message.
  2. Return the greeting message. 



```


