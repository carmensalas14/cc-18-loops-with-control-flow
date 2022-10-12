# Code Challenge: Loops with Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function named `greaterNum` that:
  - takes 4 arguments, both numbers.
  - returns whichever number is the greater (higher) number.
  - If two arguments are equal, it will return the string "two integers are equal"
  - If three arguments are equal, it will return the string "three integers are equal"
  - If all arguments are equal, it will return the string "all integers are equal"
  - If a given argument is not an integer data type it will return `null`
```
greaterNum(10, 7, 30, 60) //returns 60
greaterNum(1.14, 1.14, 3, 5) //returns "two integers are equal"
greaterNum(1.14, 1.14, 1.14, 5) //returns "three integers are equal"
greaterNum("21", 21, "3", 5) //returns null
```

2. Write a function named `sumOfNotThreeAndFive` that returns the sum of all numbers that are *not* multiples of 3 and multiples of 5 from 1 to 1000.
```
sumOfNotThreeAndFive() //returns 333666
```


### Bonus 
3. Write a function `multiplesOfFourAndSix` that **returns an array** of all positive numbers from 1 to 100 if that number is a multiple of 4 and a mutliple of 6. 
```
multiplesOfFourAndSix() // returns [12, 24, 36, 48,60, 72, 84, 96]
```

4. Write a fucntion named `countMultiplesOfTwo` that takes in an array of integers and returns the number of integers in the array that are multiples of two. 
```
countMultiplesOfTwo([1,2,3,4,5,6,7,8,9,10]) // returns 5
countMultiplesOfTwo([15,23,35,45,67]) // returns 0
countMultiplesOfTwo([2,6,14]) // returns 3
```
