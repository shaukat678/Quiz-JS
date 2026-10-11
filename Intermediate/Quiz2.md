Sure — here is the quiz in plain text with Markdown-style headings, not an MDX file.

# JavaScript Quiz: Simple to Intermediate

Topics: Callbacks, For Loops, While Loops, Try-Catch, and Operators Total Questions: 20 Total Marks: 20

Instructions: Choose one correct answer for each question.

## Section 1: Callbacks

1. What is a callback function in JavaScript?

A) A function passed as an argument to another function B) A function that always returns a value C) A function that runs only inside a loop D) A function that catches errors

2. What will be the output?

javascript
```
function greet(name, callback) {
    console.log("Hello " + name);
    callback();
}

greet("Ali", function () {
    console.log("Welcome!");
});
```

A) Welcome! followed by Hello Ali B) Hello Ali followed by Welcome! C) Hello Ali D) An error occurs

3. What will be the output?

javascript
```
function calculate(a, b, callback) {
    return callback(a, b);
}

console.log(calculate(4, 3, (x, y) => x + y));
```

A) 1 B) 7 C) 12 D) undefined

4. Which statement about callbacks is correct?

A) Every callback must be asynchronous B) A callback can execute synchronously or asynchronously C) Callbacks cannot accept parameters D) Callbacks must always be arrow functions

## Section 2: For Loops

5. What will be printed?

javascript
```
for (let i = 1; i <= 3; i++) {
    console.log(i);
}
```

A) 0, 1, 2 B) 1, 2, 3 C) 1, 2 D) 2, 3, 4

6. What will be the output?

javascript
```
let sum = 0;

for (let i = 1; i <= 4; i++) {
    sum += i;
}

console.log(sum);
```

A) 4 B) 6 C) 10 D) 15

7. How many times will this loop execute?

javascript
```
for (let i = 0; i < 5; i += 2) {
    console.log(i);
}
```

A) 2 times B) 3 times C) 4 times D) 5 times

8. What will be the output?

javascript
```
for (let i = 5; i > 2; i--) {
    console.log(i);
}
```

A) 5, 4, 3 B) 5, 4, 3, 2 C) 4, 3, 2 D) 3, 2, 1

## Section 3: While Loops

9. When does a `while` loop continue executing?

A) While its condition evaluates to true B) While its condition evaluates to false C) Only when it contains a return statement D) Only when it contains a callback

10. What will be the output?

javascript
```
let i = 1;

while (i <= 3) {
    console.log(i);
    i++;
}
```

A) 0, 1, 2 B) 1, 2, 3 C) 1, 2 D) The loop runs forever

11. What is the problem with this code?

javascript
```
let count = 0;

while (count < 5) {
    console.log(count);
}
```

A) The condition is invalid B) The loop may run forever because count never changes C) console.log() cannot be used in a loop D) A while loop cannot use numbers

12. What will be the output?

javascript
```
let x = 10;

while (x > 0) {
    x -= 3;
}

console.log(x);
```

A) 1 B) 0 C) -2 D) -3

## Section 4: Try-Catch

13. What is the purpose of a `try...catch` statement?

A) To repeat a block of code B) To handle exceptions C) To declare variables D) To create callback functions

14. What will be the output?

javascript
```
try {
    console.log("Start");
    throw new Error("Something went wrong");
    console.log("End");
} catch (error) {
    console.log("Caught an error");
}
```

A) Start, then End B) Start, then Caught an error C) Caught an error, then End D) Only End

15. Which keyword is used to throw a custom exception in JavaScript?

A) `catch` B) `error` C) `throw` D) `finally`

16. What will be the output?

javascript
```
try {
    console.log(10 / 2);
} catch (error) {
    console.log("Error occurred");
} finally {
    console.log("Finished");
}
```

A) 5, then Finished B) 5, then Error occurred C) Only Finished D) Error occurred, then Finished

## Section 5: Operators

17. What will be the output?

javascript
```
console.log(5 == "5");
console.log(5 === "5");
```

A) true, then true B) false, then false C) true, then false D) false, then true

18. What will be the output?

javascript
```
let a = 10;
let b = 3;

console.log(a % b);
```

A) 1 B) 3 C) 3.33 D) 0

19. What will be the output?

javascript
```
let x = 5;

console.log(x > 3 && x < 10);
console.log(x < 3 || x === 5);
```

A) true, then true B) true, then false C) false, then true D) false, then false

20. What will be the output?

javascript
```
let x = 5;

x += 3 * 2;

console.log(x);
```

A) 16 B) 11 C) 13 D) 10

