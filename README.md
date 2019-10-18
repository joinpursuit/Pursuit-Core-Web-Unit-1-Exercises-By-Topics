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
## Strings
## Arrays
## Objects
## Callbacks
## Array Methods
## Classes
