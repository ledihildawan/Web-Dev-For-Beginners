# Fun with Functions

## Instructions

Create different functions, both functions that return something and functions that don't return anything.

See if you can create a function that has a mix of parameters and parameters with default values.

## Rubric

| Criteria | Exemplary                                                                              | Adequate                                                         | Needs Improvement |
| -------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------- |
|          | Solution is offered with two or more well-performing functions with diverse parameters | Working solution is offered with one function and few parameters | Solution has bugs |


```js
// Function that returns something
function add(a, b) {
  return a + b;
}

// Function that doesn't return anything (just logs)
function greetUser(name) {
  console.log(`Hello, ${name}!`);
}

// Function with mix of parameters and default values
function createUserProfile(name, age = 18, isAdmin = false) {
  return {
    name,
    age,
    role: isAdmin ? "Administrator" : "User"
  };
}

// Using the functions
let sum = add(5, 10);
console.log("Sum:", sum); // Output: Sum: 15

greetUser("Alice"); // Output: Hello, Alice!

let user1 = createUserProfile("Bob");
let user2 = createUserProfile("Jane", 30, true);

console.log(user1); // Output: { name: 'Bob', age: 18, role: 'User' }
console.log(user2); // Output: { name: 'Jane', age: 30, role: 'Administrator' }
```