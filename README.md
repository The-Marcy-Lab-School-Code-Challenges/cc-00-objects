# Code Challenge: Objects

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

### **Test your solutions for questions 1 and 2 with the following variable:** 
```javascript
const associateInstructorAges = {"carmen": 22, "itzel": 22, "jowel": 27}
```

1. Write a function named `getAllKeys` that takes in an object argument and logs all the keys in the given argument to the console.

    ```javascript
    getAllKeys(associateInstructorAges) // will log to the console: "carmen", "itzel", "jowel"
    ```
    
2. Write a function named `getAllValues` that takes in an object argument and logs the value of every key in the given argument to the console.

    ```javascript
    getAllValues(associateInstructorAges) // will log to the console: 22, 22, 27
    ```
    
### Bonus
3. Write a function named `sumAllValues` that takes in an object argument and returns the sum of all the values of every key in the given argument. 
    ```javascript
    sumAllValues(associateInstructorAges) // returns 71
    ```
