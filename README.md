# Unit 1 Exercises by Topic

**Conventions:**

* In a function definition `argument:type` means that a given `argument` is of type `type`. For Example in `alarmClock(dayNum: number, onVacation:boolean) → string`:
  * `dayNum: number` means that the `dayNum` argument will/should be a number (a value of type `number`). 
  * `onVacation: boolean` means that the `onVacation` argument of the function will be a boolean. That is the value of `onVacation` will be either `true` or `false`
  * `→ string` means the function will/should return a string(a value of type `string`)

## Conditionals

### 1. [loneTeen](https://codingbat.com/prob/p165701)

We'll say that a number is "teen" if it is in the range 13..19 inclusive. Given 2 int values, return true if one or the other is teen, but not both.

**Function signature**: `loneTeen(numA, numB) → boolean`

**Sample input & output**: 
```
loneTeen(13, 99) → true
loneTeen(21, 19) → true
loneTeen(13, 13) → false
```

### 2. [caughtSpeeding](https://codingbat.com/prob/p157733)

You are driving a little too fast, and a police officer stops you. Write a function `caughtSpeeding` to compute the result, encoded as number value: 0=no ticket, 1=small ticket, 2=big ticket. If speed is 60 or less, the result is 0. If speed is between 61 and 80 inclusive, the result is 1. If speed is 81 or more, the result is 2. Unless it is your birthday -- on that day, your speed can be 5 higher in all cases.

**Function signature**: `caughtSpeeding(speed: number, isBirthday: boolean) → number`

**Sample input & output**: 
```
caughtSpeeding(60, false) → 0
caughtSpeeding(65, false) → 1
caughtSpeeding(65, true) → 0
```

### 3. [alarmClock](https://codingbat.com/prob/p160543)

Given a day of the week encoded as 0=Sun, 1=Mon, 2=Tue, ...6=Sat, and a boolean indicating if we are on vacation, return a string of the form "7:00" indicating when the alarm clock should ring. Weekdays, the alarm should be "7:00" and on the weekend it should be "10:00". Unless we are on vacation -- then on weekdays it should be "10:00" and weekends it should be "off".

**Function signature**: `alarmClock(dayNum: number, onVacation: boolean) → string`

**Sample input & output**: 
```
alarmClock(1, false) → "7:00"
alarmClock(5, false) → "7:00"
alarmClock(0, false) → "10:00"
```

### 4. [inOrder](https://codingbat.com/prob/p154188)

Given three numbers, `a`, `b` & `c`, return true if `b` is greater than `a`, and `c` is greater than `b`. However, with the exception that if `bOk` is true, `b` does not need to be greater than `a`.

**Function signature**: `inOrder(a: number, b: number, c: number, bOk: boolean) → boolean`

**Sample input & output**: 
```
inOrder(1, 2, 4, false) → true
inOrder(1, 2, 1, false) → false
inOrder(1, 1, 2, true) → true
```

## Loops

### serialIdGenerator
You work for an e-commerce warehouse. They have been manually assigning items in the inventory serial id numbers like `1658`. They are tired of doing this and ask you to write a JavaScript program to generate `n` more serial id numbers for `n` new products that will be added to the inventory.
They give you `lastId` which is the id of the last item that was added to the inventory. You should pick up from where they left.
They also give you `n` which is how many new serial id numbers they want.

Write a function that prints `n` new serial id numbers starting but not including the `lastId`.

**Function signature**: `serialIdGenerator(lastId: number, n: number) → undefined`

**Sample input & output**: 
```
serialIdGenerator(110, 10) → undefined

// Prints
111
112
113
114 
115 
116
117
118
119 
120
121
```

### multTable
Given an integer number `n` print the multiplication table for `n` times 1 to 10.

**Function signature**: `multTable(n: number) → undefined`

**Sample input & output**: 
```
multTable(2) → undefined

// Prints
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
```

### numbersEvenlyDivisibleBy

Write a function with a loop that will iterate from `min` to `max`. For each iteration, it will check if the current number is evenly divisible by `divisor` if it is, you function should print the number followed by the word 'yes', otherwise print the number followed by the word 'no'

**Function signature**: `numbersEvenlyDivisibleBy(min: number, max: number, divisor: number) → undefined`

**Sample input & output**: 
```
numberEvenlyDivisibleBy(3, 15, 3) → undefined

// Prints
3 yes
4 no
5 no
6 yes
7 no
8 no
9 yes
10 no
11 no
12 yes
13 no
14 no
15 yes
```

### marioStairs
You are one of the early developers of the now famous Super Mario Bros video game. You are in charge of writing a JavaScript program that builds the stairs Mario will use to jump over obstacles and reach the castle in the text based video game prototype. [Shigeru Miyamoto](https://en.wikipedia.org/wiki/Shigeru_Miyamoto) asks you to implement a function `marioStairs(nSteps)` that will build the a stair case of `nSteps` number of steps.

**Function signature**: `marioStairs(nSteps: number) → undefined`

**Sample input & output**: 
```
marioStairs(5) → undefined

// Prints
*  
* *  
* * *  
* * * *  
* * * * *  
```
**Hint**: You will need a nested loop
**Challenge**: You may have realized that on the final version of the Super Mari Bros game, Mario climbs stairs going right instead of left. Make your function print the stairs going right.

## Strings

### 1. [startHi](https://codingbat.com/prob/p191022)

You are writing software for a robot that needs to identify when a human is saying hi to it. You are given the task of writing a JavaScript function, that given a string that represents the speech-to-text result, returns true if the string starts with `"hi"` and false otherwise.

**Function signature**: `startHi(string) → boolean`

**Sample input & output**: 
```
startHi("hi there") → true
startHi("hi") → true
startHi("hello hi") → false
```



### reverseWord

## Arrays
## Objects
## Callbacks
## Array Methods
## Classes
