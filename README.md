# DSA-Practice

## Strings

## Question 1

You are given a string stored in variable `problem`. Write code that prints the longest word in the string.

```swift
var problem = "find the longest word in the problem description"

// Your code here
```

Example:
Input:
`var problem = "find the longest word in the problem description"`

Output:
`description`

Hint: Keep track of the longest word you encounter and also keep track of its length.


***
## Question 2

Given a string in English, create a tuple containing the number of vowels and consonants.

```swift
let vowels = "aeiou"
let consonants = "bcdfghjklmnpqrstvwxyz"
let input = "Count how many vowels I have!"
```

***
## Question 3

Given a string with multiple words. Reverse the string word by word.

Example:

Sample Input: `"Swift is the best language"`

Sample Output: `"language best the is Swift"`

***


## Question 4

You are given a string representing an **attendance record** for a student. The record only contains the following three characters:

`'A' : Absent.`

`'L' : Late.`

`'P' : Present.`

If a student has more than one 'A' or more than 2 continuous 'L's that student should not be rewarded. Print true if student is to be rewarded and False if they shouldn't.

Example:

Sample Input: `"PPALLP"`

Sample Output: `true`

***
## Question 5

Given a string of words separated by a `" "`. Write code that prints out the length of the last word.

If there is no last word print out `"No last word"`.

Example:
Input: `"How are you doing this Monday?"`

Output: `7`

***

## Arrays

***

## Question 6

Given an array of Ints, find out if it contains a target number.  

(The built-in `contains(_:)` function will do this, but you aren't allowed to use it for this exercise.)


```swift
var numbers: [Int]

let target: Int = 32
```

Ex.1

```swift
numbers = [4,2,6,73,32,4,2,1]

target = 32

//true
```

Ex. 2

```swift
numbers = [32459,2,4,5,1,4,2,1]

target = 3

//false
```

***

## Question 7

Given an Array of Tuples of type `(Int, Int)`, create an array containing all the tuples where the first Int is equal to the second Int.

Input: `[(4,2), (-3,-3), (1,1), (3,9)]`

Output: `[(-3,-3), (1,1)]`



## Question 8

Print out each element in `myMatrix`

`var myMatrix = [[10, 14, 12], [91, 1, 9], [31, 3, 21]]`


## Question 9

Print out the sum of the diagonals of `myMatrix`.

`var myMatrix = [[10, 14, 12], [91, 1, 9], [31, 3, 21]]`


## Question 10

Using for loops, rotate `matrixToRotate` 90 degrees.

var matrixToRotate = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

![Matrix Rotation](images/rotated_matrix.jpeg)

***

## Functions

***

## Question 11
Write a function that prints the numbers from 1 to x, except:

If the number if a multiple of 3, print "Fizz" instead of the number If the number is a multiple of 5, print "Buzz" instead of the number If the number is a multiple of 3 AND 5, print "FizzBuzz" instead of the number Your function should take in one parameter: x (the number to count up to)
```swift

// Your code here
```



## Question 12
Write a function named reverse that takes an array of integers named numbers as a parameter. The function should return an array with the numbers from numbers in reverse order.

Example: Input: reverse([1, 2, 3])

Output: [3, 2, 1]

```swift

// Your code here
```

## Question 13
Write a function that prints out the most frequently appearing Int in an array of Int.

```swift

// Your code here
```

## Question 14
Write a function that sums all the even indices of an array of Ints.
```swift

// Your code here
```

## Question 15
Write a function that finds the person with the second highest test score in a Dictionary that maps names to scores.

Example: Input: ["Person 1": 83, "Person 2": 74, "Person 3": 82]

Output: "Person 3"
```swift

// Your code here
```

