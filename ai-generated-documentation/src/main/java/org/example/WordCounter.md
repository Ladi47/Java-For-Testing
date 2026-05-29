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
     - **Description:** This is the entry point of the program. It defines a sample sentence, splits it into words, and prints the word count to the console.
     - **Parameters:** `args`: An array of strings representing command-line arguments (not used in this program).
     - **Return Values:** None.
     - **Important Logic:**
       1. Defines a sample sentence: `"Java is fun to learn"`.
       2. Uses `trim()` method to remove leading and trailing whitespace from the sentence.
       3. Splits the trimmed sentence into an array of words using `split("\\s+")`, where "\\s+" matches one or more whitespace characters.
       4. Prints the length of the resulting word array, which represents the word count, using `System.out.println()`.

**5. Key Variables and Data Structures:**

   - **`sentence` (String):** Stores the input sentence for analysis.
   - **`words` (String[]):** An array of strings representing individual words extracted from the sentence.


**6. Dependencies and Libraries:**

   - This program uses standard Java libraries:
     - `java.lang.String`: For string manipulation operations like trimming and splitting.
     - `java.util.Arrays`: For accessing array length (although not explicitly used in this example).



**7. Pseudo Code:**

```
// Class: WordCounter

// Method: main()
  1. Define a sample sentence: "Java is fun to learn".
  2. Remove leading and trailing whitespace from the sentence using the trim() method.
  3. Split the trimmed sentence into an array of words based on whitespace characters using the split("\\s+") method.
  4. Calculate the length of the resulting word array.
  5. Print the calculated word count to the console. 

```



