![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## FindMaxInArray.java Documentation

Overview:

This Java program finds the maximum value within a given integer array. It iterates through each element of the array, comparing it to the current maximum value. If a larger element is found, the maximum value is updated. Finally, the program prints the maximum value found in the array.

Package/module name: org.example

 Class/file name: FindMaxInArray.java

Detailed Documentation:

   - **`main(String[] args)`:**
     - **Description:** This is the main method of the program, where execution begins. It initializes an integer array, finds the maximum value within the array, and prints the result.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Initializes an integer array `arr` with sample values.
       - Sets the initial maximum value (`max`) to the first element of the array.
       - Iterates through each element (`n`) in the array using a for-each loop.
       - For each element, it compares `n` with the current `max`. If `n` is greater than `max`, `max` is updated to `n`.
       - After iterating through all elements, prints the final value of `max`, which represents the maximum value found in the array.

Pseudo Code:


```
// Class: FindMaxInArray

// Method: main(String[] args)
  1. Initialize an integer array 'arr' with sample values {4, 12, 7, 9}.
  2. Set variable 'max' to the first element of 'arr' (value 4).
  3. Iterate through each element 'n' in the array 'arr':
     - If 'n' is greater than 'max', update 'max' to 'n'.
  4. Print the value of 'max', which represents the maximum value found in the array.
```



Dependencies and Libraries:

This program does not rely on any external libraries. It utilizes built-in Java functionalities for array manipulation and printing output. 


