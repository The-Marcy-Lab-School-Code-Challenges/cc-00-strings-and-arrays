# Code Challenge: Strings and Arrays

## Instructions

1. Clone down this assignment to your `code-challenges' directory.
2. Code your solution using JavaScript in `index.js`.
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Declare a function called `stripUpperCase` that takes in a string argument consistenting of only alphabet characters and returns a new string with all uppercase letters removed.
    
    ```jsx
    stripUpperCase('Hello'); // 'ello'
    stripUpperCase('SevenEleven'); // 'evenleven'
    stripUpperCase("code challenge is fun"); // 'code challenge is fun'
    
    ```
    
2. Declare a function named `findLongestWord`, that takes an array of strings as an argument, and returns the longest string in the array. If there is more than one longest string, the function should return the **first** longest string that appears in the array. You must solve this without using any array methods.
    
    ```jsx
    findLongestWord(["The","quick","brown", "fox", "jumped", "over", "the", "lazy", "dog"]) //returns "jumped"
    
    findLongestWord(["jazzy", "jumpy", "quaky"]) //returns "jazzy"
    
    ```
