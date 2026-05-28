![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## WordCounter.java Documentation

**1. Overview:**

This Java program counts the number of words in a given sentence. It takes a string as input, splits it into individual words based on whitespace, and then returns the count of these words. 

**2. Package/module name:** org.example

**3. Class/file name:** WordCounter.java

**4. Detailed Documentation:**

   - **`main(String[] args)`:**
     - **Description:** This is the entry point of the program. It defines a sample sentence, splits it into words, and prints the word count.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       - Defines a string variable `sentence` containing the input text.
       - Uses `sentence.trim()` to remove leading and trailing whitespace from the sentence.
       - Splits the trimmed sentence into an array of strings (`words`) using `split("\\s+")`, where "\\s+" matches one or more whitespace characters.
       - Prints the length of the `words` array, which represents the word count, using `System.out.println(words.length)`.

**5. Key Variables and Data Structures:**

   - **`sentence`**: A string variable holding the input sentence.
   - **`words`**: A String array containing individual words extracted from the sentence.

**6. Dependencies and Libraries:**

   - This program relies on standard Java libraries for string manipulation (`String`, `split()`) and output (`System.out.println()`).


**7. Pseudo Code:**

```
// Class: WordCounter

// Method: main()
  1. Define a string variable "sentence" with the input text.
  2. Remove leading and trailing whitespace from "sentence" using trim().
  3. Split "sentence" into an array of strings "words" based on one or more whitespace characters.
  4. Print the length of the "words" array, representing the word count. 



```




