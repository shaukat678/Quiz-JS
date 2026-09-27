---

**Topics:** `let`, `var`, `const`, Global Scope, Block Scope, Arrays, Objects, Nested Arrays/Objects, `if/else`
**Level:** Easy
**Answers:** Not included

---

## Part A — `let`, `var`, `const`

### 1. Which keyword is commonly used when you want to declare a variable whose value can change?

A. `let`
B. `const`
C. `fixed`
D. `static`

---

### 2. Which keyword is used to declare a constant variable?

A. `let`
B. `var`
C. `const`
D. `constant`

---

### 3. What happens here?

```javascript
let age = 20;
age = 21;

console.log(age);
```

A. `20`
B. `21`
C. `undefined`
D. Error

---

### 4. What happens here?

```javascript
const name = "Ali";
name = "Ahmed";
```

A. `name` becomes `"Ahmed"`
B. `name` becomes `undefined`
C. An error occurs
D. Nothing happens

---

### 5. Which variable declaration allows redeclaration in the same scope?

A. `let`
B. `const`
C. `var`
D. None

---

### 6. Which of the following is valid?

A.

```javascript
const age;
```

B.

```javascript
let age = 20;
```

C.

```javascript
let = age 20;
```

D.

```javascript
variable age = 20;
```

---

### 7. What will be printed?

```javascript
let x = 10;
x = 20;

console.log(x);
```

A. `10`
B. `20`
C. `undefined`
D. Error

---

### 8. Which statement about `const` is correct?

A. A `const` variable can always be reassigned
B. A `const` variable must be initialized when declared
C. `const` variables are always global
D. `const` can only store numbers

---

## Part B — Scope

### 9. What is the scope of a variable declared outside all functions and blocks?

A. Local scope
B. Block scope
C. Global scope
D. Loop scope

---

### 10. What is block scope?

A. A variable available everywhere in the program
B. A variable available only inside a block such as `{ }`
C. A variable available only inside an object
D. A variable available only inside an array

---

### 11. What will happen?

```javascript
if (true) {
    let message = "Hello";
}

console.log(message);
```

A. Prints `Hello`
B. Prints `undefined`
C. Error occurs
D. Prints `true`

---

### 12. What will happen?

```javascript
if (true) {
    var message = "Hello";
}

console.log(message);
```

A. `Hello`
B. `undefined`
C. Error
D. `true`

---

### 13. Which keywords are block-scoped?

A. Only `var`
B. `let` and `const`
C. Only `const`
D. `var` and `let`

---

### 14. What will be printed?

```javascript
let x = 10;

if (true) {
    let x = 20;
    console.log(x);
}

console.log(x);
```

A. `20` then `20`
B. `10` then `10`
C. `20` then `10`
D. `10` then `20`

---

### 15. Which variable is accessible outside the block?

```javascript
if (true) {
    // ?
}
```

A. A `let` variable declared inside the block
B. A `const` variable declared inside the block
C. A `var` variable declared inside the block
D. None of them

---

## Part C — Arrays

### 16. Which is a valid JavaScript array?

A.

```javascript
let fruits = ("apple", "banana", "mango");
```

B.

```javascript
let fruits = ["apple", "banana", "mango"];
```

C.

```javascript
let fruits = {"apple", "banana", "mango"};
```

D.

```javascript
let fruits = <"apple", "banana", "mango">;
```

---

### 17. What is the index of the first element of an array?

A. `0`
B. `1`
C. `-1`
D. `first`

---

### 18. What will be printed?

```javascript
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits[0]);
```

A. `Apple`
B. `Banana`
C. `Mango`
D. `0`

---

### 19. What will be printed?

```javascript
let numbers = [10, 20, 30, 40];

console.log(numbers[2]);
```

A. `10`
B. `20`
C. `30`
D. `40`

---

### 20. How do you find the number of elements in an array?

A. `array.size`
B. `array.length`
C. `array.count`
D. `array.total`

---

### 21. What will this print?

```javascript
let fruits = ["Apple", "Banana"];

fruits.push("Mango");

console.log(fruits);
```

A. `["Apple", "Banana"]`
B. `["Mango", "Apple", "Banana"]`
C. `["Apple", "Banana", "Mango"]`
D. Error

---

## Part D — Objects

### 22. Which is a valid JavaScript object?

A.

```javascript
let person = ["name": "Ali"];
```

B.

```javascript
let person = {
    name: "Ali",
    age: 20
};
```

C.

```javascript
let person = ("name", "Ali");
```

D.

```javascript
let person = <name = "Ali">;
```

---

### 23. How can you access the `name` property?

```javascript
let person = {
    name: "Ali",
    age: 20
};
```

A. `person.name`
B. `person->name`
C. `person[name()]`
D. `person::name`

---

### 24. What will be printed?

```javascript
let student = {
    name: "Ahmed",
    age: 21
};

console.log(student.age);
```

A. `Ahmed`
B. `21`
C. `age`
D. `undefined`

---

### 25. Which syntax accesses an object property using bracket notation?

A. `person.name`
B. `person->name`
C. `person["name"]`
D. `person(name)`

---

## Part E — Nested Arrays & Objects

### 26. What will be printed?

```javascript
let numbers = [
    [1, 2],
    [3, 4]
];

console.log(numbers[0][1]);
```

A. `1`
B. `2`
C. `3`
D. `4`

---

### 27. What will be printed?

```javascript
let students = [
    { name: "Ali", age: 20 },
    { name: "Ahmed", age: 22 }
];

console.log(students[1].name);
```

A. `Ali`
B. `Ahmed`
C. `20`
D. `22`

---

### 28. What does this represent?

```javascript
let student = {
    name: "Ali",
    address: {
        city: "Karachi",
        country: "Pakistan"
    }
};
```

A. An array inside an object
B. An object inside an object
C. An object inside an array
D. Two separate objects

---

## Part F — `if / else`

### 29. What will be printed?

```javascript
let marks = 75;

if (marks >= 50) {
    console.log("Pass");
} else {
    console.log("Fail");
}
```

A. `Pass`
B. `Fail`
C. `75`
D. Error

---

### 30. What will be printed?

```javascript
let age = 15;

if (age >= 18) {
    console.log("Adult");
} else {
    console.log("Minor");
}
```

A. `Adult`
B. `Minor`
C. `15`
D. Nothing
