# Types Variables Logic and Operations Lab

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## 1. Which data type would be the best to use for recording the total balance of an online shopping cart?

// your answer here
Double
***
## 2. Which of the following variable declarations is **incorrect**?

```swift
let isClosed: Bool = false

let version: Double = 3.0

let emotion: String = ":)"

let grade: Char = "a"
```
"let grade: Char = "a" is not correct!!! because it is an incorrect annotation"

***
## 3. Simplify the following using a calculator:

1 + 4 * 2 / 2 + 2

The answer is 7

***
## 4. Which of the following are true? State all that apply.

```swift
17 % 4 == 1

25 % 4 != 1

81 % 9 != 840 % 2

(14 % 2 < 4) || (243 % 13 > 2) || (52 % 3 > 5)
```
17 % 4 == 1    // This is true!!

25 % 4 != 1   // This is false

81 % 9 != 840 % 2  // This is false

(14 % 2 < 4) | | (243 % 13 > 2) | | (52 % 3 > 5) // This is false

***
## 5. Which of the follow is true?

a)
```swift
let numOne = 4.0
let numTwo = 4.0
let a = numOne == numTwo
```
b)
```swift
let numThree = 24/5
let numFour = 24.0/5.0
let b = numThree == numFour
```
c)
```swift
let numFive = 24%5
let numSix = 24.0%5.0
let c = numFive == numSix
```
d)
```swift
let numSeven = 4.0 + 1.2
let numEight = 5.0 + .2
let d = numSeven == numEight
```

A) is true because numOne and numTwo have the same value. Every other statement is false

***
## 6. What is the final value of i?

```swift
var i = 0
i = 5
i += 3
i *= 2
i %= 3
i -= 3

```
Step 1: i is 5
Step 2: 5 + 3, i is now 8
Step 3: 8 x 2, i is now 16
Step 4: 16 % 3, i is now 1 because 5x3 and 1 is leftover
Step 5: 1 - 3, i is now -2
