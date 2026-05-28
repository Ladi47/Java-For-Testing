![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Palindrome.java Documentation

**1. Overview:**

This Java program determines whether a given word is a palindrome. A palindrome is a word or phrase that reads the same backward as forward (e.g., "level", "racecar"). The program takes a string input and compares each character from the beginning and end of the string, moving inwards. If any pair of characters doesn't match, it concludes the word is not a palindrome.

**2. Package/module name:** org.example

**3. Class/file name:** Palindrome.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It initializes a sample word, sets up a boolean flag to track if it's a palindrome, and calls the `isPalindrome()` function to check the word. Finally, it prints the result to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Sets a sample word "level" to the `word` variable.
       - Initializes a boolean variable `isPalindrome` to `true`, assuming the word is a palindrome until proven otherwise.
       - Calls the `isPalindrome()` function, passing the `word` as an argument.
       - Prints the value of `isPalindrome` (true or false) to the console.

   - **`isPalindrome(String word)`:** 
     - **Description:** This function checks if a given string is a palindrome. It iterates through the string, comparing characters from both ends towards the middle. If any mismatch occurs, it sets `isPalindrome` to `false` and breaks the loop.
     - **Parameters:** `word`: The input string to be checked for palindromicity.
     - **Return Values:** Returns `true` if the word is a palindrome, `false` otherwise.
     - **Important Logic:**
       - Uses two index variables, `i` starting at 0 (beginning of the string) and `j` starting at the last index (`word.length() - 1`) (end of the string).
       - Iterates using a `for` loop as long as `i` is less than `j`.
       - In each iteration, it compares the characters at indices `i` and `j`:
         - If they are different, sets `isPalindrome` to `false` and breaks out of the loop.
       - If all characters match until the middle, `isPalindrome` remains `true`, indicating a palindrome.



**5. Key Variables and Data Structures:**

   - **`word` (String):** Stores the input string to be checked for palindromicity.
   - **`isPalindrome` (boolean):** A flag variable that indicates whether the word is a palindrome (`true`) or not (`false`).


**6. Dependencies and Libraries:**

   - This code relies on standard Java libraries:
     - `java.lang.String`: For string manipulation.
     - `java.util.Scanner`: (Not used in this example, but often used for user input)



**7. Pseudo Code:**



```
// Class: Palindrome

// Method: main(String[] args)
  1. Set a sample word to the 'word' variable.
  2. Initialize 'isPalindrome' to true.
  3. Call the 'isPalindrome()' function, passing 'word' as an argument.
  4. Print the value of 'isPalindrome'.

// Method: isPalindrome(String word)
  1. Initialize two index variables: 
    - 'i' starting at 0 (beginning of the string).
    - 'j' starting at the last index of the string ('word.length() - 1').
  2. Loop while 'i' is less than 'j':
    - Compare the characters at indices 'i' and 'j'.
      - If they are different:
        - Set 'isPalindrome' to false.
        - Break out of the loop.
    - Increment 'i' and decrement 'j'.
  3. Return 'isPalindrome'.



```




