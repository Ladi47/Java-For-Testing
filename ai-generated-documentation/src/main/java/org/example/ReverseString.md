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
     - **Description:** This is the entry point of the program. It initializes a string, reverses it using a loop, and prints the reversed string.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Declares a string variable `input` and initializes it with the value "hello".
       2. Declares an empty string variable `reversed` to store the reversed string.
       3. Uses a `for` loop to iterate through the characters of the `input` string in reverse order (from the last character to the first).
         - In each iteration, it appends the current character (`input.charAt(i)`) to the `reversed` string.
       4. After the loop completes, prints the value of `reversed` to the console.

**5. Key Variables and Data Structures:**

   - **`input` (String):** Stores the original string that needs to be reversed.
   - **`reversed` (String):** Stores the reversed version of the input string.


**6. Dependencies and Libraries:**

   - This program uses standard Java libraries:
     - `java.lang.String`: For string manipulation operations like `charAt()` and concatenation (`+=`).



**7. Pseudo Code:**



```
// Class: ReverseString

// Method: main()
  1. Set input string to "hello".
  2. Create an empty string called "reversed".
  3. Iterate through the input string from the last character to the first:
    - For each character in the input string:
      - Append the current character to the "reversed" string.
  4. Print the "reversed" string to the console. 



```




