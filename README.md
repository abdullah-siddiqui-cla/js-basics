# Javascript Language Basics

## Practice 1
Write a program that logs to the console numbers from 1 to 50. But for multiples of 3, print "Fizz" instead of the number, and for multiples of 5, print "Buzz". For numbers that are multiples of both 3 and 5, print "FizzBuzz".

## Practice 2 
Write a program that takes student's grade (a number between 0 and 100) and logs to the console whether the student is passed or failed (passing grade is 50 or above). 
**NOTES**: 
- Feel free to extand the grading using A, B, C, D , F grades
- Use the following javascript to take input from the user:
    ```js
    let input = parseInt(prompt("Enter your grade:"));
    ```
- Think of different edge cases and handle them

## Practice 3
Write a progrma tha calculates the sum of all numbers between 1 and a user-specified number
##### Example
- User's input: `5`
- Program's output: `15` (1 + 2 + 3 + 4 + 5)
**NOTES**:
- Use the following javascript to take input from the user:
    ```js
    let input = parseInt(prompt("Enter your number:"));
    ```
## Practice 4
Write a program that prints the multiplication table up to 7 of a number entered by the user
##### Example
- User's input: `3`
- Program's output:
    > 3 x 1 = 3

    > 3 x 2 = 6

    > 3 x 3 = 9

    > ...

    > 3 x 7 = 21

## Practice 5
Create a program that generates the first `n` numbers in the Fibonacci sequence. The Fibonacci sequence starts with 0 and 1, and each subsequent number is the sum of the previous two
##### Example
- `n` = 7
- Program's output: 0, 1, 1, 2, 3, 5, 8
**NOTES**:
- Use the following javascript to take input from the user:
    ```js
    let input = parseInt(prompt("Enter 'n':"));
    ```