![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## ReverseString.java Documentation

**1. Overview:**

This Java program takes a string as input and reverses its order of characters. It then prints the reversed string to the console. 

**2. Package/module name:** org.example

**3. Class/file name:** ReverseString.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It initializes a string, reverses it using a loop, and prints the reversed string to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Declares a string variable `input` and assigns it the value "hello".
       2. Declares an empty string variable `reversed`.
       3. Iterates through each character of the `input` string in reverse order using a `for` loop:
         - The loop starts from the last index (`input.length() - 1`) and goes down to 0.
         - In each iteration, it appends the current character (`input.charAt(i)`) to the `reversed` string.
       4. Prints the `reversed` string using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - **`input` (String):** Stores the original string to be reversed.
   - **`reversed` (String):** Stores the reversed version of the input string.


**6. Dependencies and Libraries:**

   - This program uses standard Java libraries:
     - `java.lang.String`: For string manipulation operations like `length()`, `charAt()`, and concatenation (`+=`).



**7. Pseudo Code:**

```
// Class: ReverseString

// Method: main()
  1. Set input string to "hello"
  2. Create an empty string called "reversed"
  3. Iterate through each character of the "input" string in reverse order (from last character to first):
    - Append the current character from "input" to the "reversed" string
  4. Print the "reversed" string 



```




