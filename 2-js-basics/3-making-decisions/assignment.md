# Operators

## Instructions

Play around with operators. Here's a suggestion for a program you can implement:

You have a set of students from two different grading systems.

### First grading system

One grading system is defined as grades being from 1-5 where 3 and above means you pass the course.

### Second grading system

The other grade system has the following grades `A, A-, B, B-, C, C-` where `A` is the top grade and `C` is the lowest passing grade.

### The task

Given the following array `allStudents` representing all students and their grades, construct a new array `studentsWhoPass` containing all students who pass.

> TIP, use a for-loop and if...else and comparison operators:

```javascript
let allStudents = [
  'A',
  'B-',
  1,
  4,
  5,
  2
]

let studentsWhoPass = [];
```

## Rubric

| Criteria | Exemplary                      | Adequate                      | Needs Improvement               |
| -------- | ------------------------------ | ----------------------------- | ------------------------------- |
|          | Complete solution is presented | Partial solution is presented | Solution with bugs is presented |

```js
let allStudents = ['A', 'B-', 1, 4, 5, 2];
let studentsWhoPass = [];

for (let i = 0; i < allStudents.length; i++) {
  let grade = allStudents[i];

  // Check if the grade is a number (first grading system)
  if (typeof grade === "number") {
    if (grade >= 3 && grade <= 5) {
      studentsWhoPass.push(grade);
    }
  } 
  // Otherwise assume it's a letter grade (second grading system)
  else if (typeof grade === "string") {
    if (grade === "A" || grade === "A-" || grade === "B" || grade === "B-" || grade === "C") {
      studentsWhoPass.push(grade);
    }
  }
}

console.log("Students who pass:", studentsWhoPass);
```