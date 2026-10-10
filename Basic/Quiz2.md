# JavaScript Quiz — 30 Questions

**Topics:** Arrays, Objects, Nested Objects, Functions, and For Loops

**Instructions:** Choose the correct option (A, B, C, or D). Do not use an answer key.

## Section 1: Arrays

### Q1. What is the output?
```javascript
let arr = [10, 20, 30, 40];
console.log(arr[1]);
```
- A) 10
- B) 20
- C) 30
- D) 40

### Q2. What is the index of the first element in an array?
```javascript
let fruits = ["Apple", "Mango", "Banana"];
```
- A) 1
- B) 0
- C) -1
- D) 3

### Q3. What is the output?
```javascript
let nums = [5, 10, 15, 20];
console.log(nums.length);
```
- A) 3
- B) 4
- C) 5
- D) 20

### Q4. Which method adds an element to the end of an array?
- A) `pop()`
- B) `shift()`
- C) `push()`
- D) `unshift()`

### Q5. What is the output?
```javascript
let arr = [1, 2, 3];
arr.push(4);
console.log(arr);
```
- A) `[4, 1, 2, 3]`
- B) `[1, 2, 3]`
- C) `[1, 2, 3, 4]`
- D) `[1, 2, 4]`

### Q6. What is the output?
```javascript
let colors = ["Red", "Blue", "Green"];
colors.pop();
console.log(colors);
```
- A) `["Blue", "Green"]`
- B) `["Red", "Blue"]`
- C) `["Red", "Blue", "Green"]`
- D) `["Green"]`

## Section 2: Objects

### Q7. How do you access the `name` property?
```javascript
let user = { name: "Ali", age: 18 };
```
- A) `user->name`
- B) `user.name`
- C) `user(name)`
- D) `user:name`

### Q8. What is the output?
```javascript
let car = { brand: "Toyota", year: 2022 };
console.log(car.brand);
```
- A) `brand`
- B) `Toyota`
- C) `2022`
- D) `undefined`

### Q9. Which is valid bracket notation?
```javascript
let student = { name: "Sara" };
```
- A) `student(name)`
- B) `student.name()`
- C) `student["name"]`
- D) `student->name`

### Q10. What is the output?
```javascript
let person = { age: 20 };
person.age = 25;
console.log(person.age);
```
- A) 20
- B) 25
- C) `undefined`
- D) Error

### Q11. How do you add a `city` property?
```javascript
let person = { name: "Ahmed" };
```
- A) `person.push("city")`
- B) `person.city = "Karachi"`
- C) `person.add("city")`
- D) `person.name = "city"`

### Q12. What is the output?
```javascript
let book = { title: "JavaScript", price: 500 };
console.log(book.author);
```
- A) `JavaScript`
- B) 500
- C) `null`
- D) `undefined`

## Section 3: Nested Objects

### Q13. What is the output?
```javascript
let user = {
  name: "Ali",
  address: { city: "Karachi" }
};

console.log(user.address.city);
```
- A) `Ali`
- B) `address`
- C) `Karachi`
- D) `undefined`

### Q14. How do you access the `street` property?
```javascript
let home = {
  address: { street: "Main Road" }
};
```
- A) `home.street`
- B) `home.address.street`
- C) `home["street"].address`
- D) `home.address[street]`

### Q15. What is the output?
```javascript
let school = {
  student: { name: "Sara", marks: 90 }
};

console.log(school.student.marks);
```
- A) `Sara`
- B) `student`
- C) 90
- D) `undefined`

### Q16. What is the output?
```javascript
let data = { a: { b: { c: 15 } } };
console.log(data.a.b.c);
```
- A) `a`
- B) `b`
- C) 15
- D) `undefined`

### Q17. Which expression accesses the price?
```javascript
let product = {
  details: { price: 500 }
};
```
- A) `product.price`
- B) `product.details.price`
- C) `product[price].details`
- D) `product.details`

### Q18. What is the output?
```javascript
let user = {
  profile: { city: "Lahore" }
};

user.profile.city = "Karachi";
console.log(user.profile.city);
```
- A) `Lahore`
- B) `Karachi`
- C) `profile`
- D) Error

## Section 4: Functions

### Q19. Which syntax correctly declares a JavaScript function?
- A) `function greet() {}`
- B) `def greet() {}`
- C) `create greet() {}`
- D) `func greet() {}`

### Q20. What is the output?
```javascript
function add(a, b) {
  return a + b;
}

console.log(add(3, 4));
```
- A) 34
- B) 7
- C) `undefined`
- D) Error

### Q21. What does the `return` statement do?
- A) Repeats the function
- B) Returns a value to the caller
- C) Always prints a value
- D) Declares a variable

### Q22. What is the output?
```javascript
function greet(name) {
  return "Hello " + name;
}

console.log(greet("Ali"));
```
- A) `Hello name`
- B) `Ali`
- C) `Hello Ali`
- D) `undefined`

### Q23. What is the output?
```javascript
function multiply(a, b = 2) {
  return a * b;
}

console.log(multiply(5));
```
- A) 5
- B) 7
- C) 10
- D) `undefined`

### Q24. What is the output?
```javascript
function test() {
  return 10;
  console.log(20);
}

console.log(test());
```
- A) 10
- B) 20
- C) 10 then 20
- D) `undefined`

## Section 5: For Loops

### Q25. How many times does this loop run?
```javascript
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```
- A) 4
- B) 5
- C) 6
- D) Infinite times

### Q26. What is the output?
```javascript
for (let i = 1; i <= 3; i++) {
  console.log(i);
}
```
- A) `0, 1, 2`
- B) `1, 2, 3`
- C) `1, 2`
- D) `0, 1, 2, 3`

### Q27. What is the final value of `sum`?
```javascript
let sum = 0;

for (let i = 1; i <= 4; i++) {
  sum += i;
}

console.log(sum);
```
- A) 4
- B) 6
- C) 10
- D) 15

### Q28. How many times will `"Hello"` be printed?
```javascript
for (let i = 0; i < 3; i++) {
  console.log("Hello");
}
```
- A) 1 time
- B) 2 times
- C) 3 times
- D) 4 times

### Q29. What is the output?
```javascript
let nums = [10, 20, 30];

for (let i = 0; i < nums.length; i++) {
  console.log(nums[i]);
}
```
- A) 10 only
- B) `10, 20, 30`
- C) `0, 1, 2`
- D) `30, 20, 10`

### Q30. What is the output?
```javascript
for (let i = 5; i >= 1; i -= 2) {
  console.log(i);
}
```
- A) `5, 4, 3, 2, 1`
- B) `5, 3, 1`
- C) `1, 3, 5`
- D) `5, 3, 2`

---

**End of Quiz**

**Total Questions:** 30

