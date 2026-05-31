# Q6 - Filter Numbers Greater Than 5 Using Array.filter()

## Objective

Create a JavaScript program that filters an array and returns only the numbers that are greater than 5 using the `Array.filter()` method.

---

## Problem Statement

Given the following array:

```javascript
const inputArr = [1, 2, 3, 9, 10, 7, 5, 4, 3];
```

Expected Output:

```javascript
[9, 10, 7]
```

Use the `filter()` method to return all numbers greater than 5.

---

## JavaScript Code

```javascript
const inputArr = [1, 2, 3, 9, 10, 7, 5, 4, 3];

const answer = inputArr.filter(num => num > 5);

console.log(answer);
```

---

## Output

```javascript
[9, 10, 7]
```

---

## Explanation

### Step 1: Create the Array

```javascript
const inputArr = [1, 2, 3, 9, 10, 7, 5, 4, 3];
```

This array contains several numbers.

### Step 2: Apply filter()

```javascript
inputArr.filter(num => num > 5);
```

The `filter()` method checks each element of the array.

### Step 3: Condition Check

```javascript
num > 5
```

Only numbers greater than 5 are selected.

### Step 4: Store the Result

```javascript
const answer = inputArr.filter(num => num > 5);
```

The filtered numbers are stored in the `answer` variable.

---

## How filter() Works

The `filter()` method creates a new array containing only the elements that satisfy a given condition.

### Syntax

```javascript
array.filter(function(element) {
    return condition;
});
```

or

```javascript
array.filter(element => condition);
```

---

## Example

Input Array:

```javascript
[1, 2, 3, 9, 10, 7, 5, 4, 3]
```

Condition:

```javascript
num > 5
```

Filtered Elements:

```javascript
9
10
7
```

Output:

```javascript
[9, 10, 7]
```

---

## Test Cases

### Test Case 1

```javascript
const arr = [2, 6, 8, 1];
```

Output:

```javascript
[6, 8]
```

### Test Case 2

```javascript
const arr = [5, 4, 3];
```

Output:

```javascript
[]
```

### Test Case 3

```javascript
const arr = [11, 12, 13];
```

Output:

```javascript
[11, 12, 13]
```

---

## Advantages of filter()

* Creates a new array without modifying the original array.
* Easy to read and maintain.
* Useful for searching and filtering data.
* Commonly used in React and modern JavaScript applications.

---

## Learning Outcomes

After completing this task, you will understand:

* Arrays in JavaScript
* Arrow Functions
* Array.filter() Method
* Conditional Filtering
* Working with New Arrays

---

## Author

JavaScript Assignment – Filtering Array Elements Using `Array.filter()`.
