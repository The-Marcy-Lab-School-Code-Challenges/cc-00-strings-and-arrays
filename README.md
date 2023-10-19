# Code Challenge: Strings and Arrays

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Declare a function called `stripUpperCase` that takes in a string argument and returns a new string with all uppercase letters removed.
```javascript
stripUpperCase('Hello!'); // 'ello!'
stripUpperCase('SevenEleven'); // 'evenleven'
stripUpperCase("Don't play with Me!"); // 'ont play with e!'
```

2. Declare a function named `findLongestWord`, that takes an array of strings as an argument, and returns the longest string in the array. If there is more than one longest string, the function should return the **first** longest string that appears in the array. You must solve this without using any array methods. 
```javascript
findLongestWord(["The","quick","brown", "fox", "jumped", "over", "the", "lazy", "dog"]) //returns "jumped"

findLongestWord(["jazzy", "jumpy", "quaky"]) //returns "jazzy"
```

3. Declare a function named `replaceWithYerr` that accepts three arguments: an Array, a start index, and the number of elements to replace with the string 'yerr'. The function should return a **new** Array, with the same elements as the original Array, except elements at the starting index, are replaced with the string 'yerr'. The number of elements replaced is determined by the third argument. Implement this function without using `.splice()`.
```js
const months = ['Jan', 'February', 'March', 'April', 'May', 'June'];

replaceWithYerr(months, 1, 3) //['Jan', 'yerr', 'yerr, 'yerr', 'May', 'June']
```

**Bonus**: Refactor your function so that the second and third arguments are *optional*. If the third argument is missing, the function should return a new array that replaces all elements from the starting index to the end of the array. If only an one argument is passed, it should return a new array argument, with all elements replaced that is the same length as the input array.
```js
const months = ['Jan', 'February', 'March', 'April', 'May', 'June'];

replaceWithYerr(months, 1) //['Jan', 'yerr', 'yerr, 'yerr', 'yerr', 'yerr']
replaceWithYerr(months) //['yerr', 'yerr', 'yerr, 'yerr', 'yerr', 'yerr']
```

