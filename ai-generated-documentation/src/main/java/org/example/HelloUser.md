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
     - **Description:** This is the main method of the program, where execution begins. It handles user input, calls the `helloUser` function, and displays the output.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Creates a `Scanner` object to read user input from the console.
       2. Prompts the user to enter their name using `System.out.print`.
       3. Reads the user's input as a string using `scanner.nextLine()`.
       4. Calls the `helloUser` function with the entered name and prints the returned greeting message using `System.out.println`.
       5. Closes the `Scanner` object to release resources using `scanner.close()`.

**5. Key Variables and Data Structures:**

   - **`name` (String):** Stores the user's inputted name.
   - **`scanner` (Scanner):** An object used to read user input from the console.


**6. Dependencies and Libraries:**

   - **java.util.Scanner:** This class is part of the standard Java library and is used for reading user input from various sources, including the console. 
   - Equivalent libraries in other languages:
     - Python: `input()` function or `sys.stdin` for reading from standard input.
     - C++: `std::cin` for reading from standard input.

**7. Pseudo Code:**


```
// Class: HelloUser

// Method: main(String[] args)
  1. Create a Scanner object to read user input.
  2. Display the prompt "Enter your name: ".
  3. Read the user's input as a string and store it in the 'name' variable.
  4. Call the helloUser function, passing the 'name' variable as an argument.
  5. Print the returned greeting message to the console.
  6. Close the Scanner object.

// Function: helloUser(String name)
  1. Concatenate the strings "Hello ", the provided 'name', and "!" to create the greeting message.
  2. Return the greeting message. 



```




