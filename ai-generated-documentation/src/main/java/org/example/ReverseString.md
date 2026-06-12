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
       - Declares a string variable `input` and initializes it with the value "hello".
       - Declares an empty string variable `reversed` to store the reversed string.
       - Uses a `for` loop to iterate through the characters of the `input` string in reverse order (from the last character to the first).
       - In each iteration, it appends the current character (`input.charAt(i)`) to the `reversed` string.
       - After the loop completes, prints the `reversed` string using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - **`input`**: A String variable holding the original input string ("hello").
   - **`reversed`**: A String variable that stores the reversed version of the input string.

**6. Dependencies and Libraries:**

   - This program relies on standard Java libraries for string manipulation (`String`, `charAt()`) and output (`System.out.println()`).


**7. Pseudo Code:**

```
// Class: ReverseString

// Method: main()
  1. Set input string to "hello".
  2. Create an empty string called "reversed".
  3. Iterate through the input string from the last character to the first:
    - For each character in the input string:
      - Append the current character to the "reversed" string.
  4. Print the "reversed" string. 



```




