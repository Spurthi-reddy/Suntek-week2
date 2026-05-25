# Week 2 JavaScript Practice

This repository contains the JavaScript practice tasks completed during Week 2.

## Overview

The work is grouped into small demos covering:

- Object copying and spread syntax
- Error handling
- Fetch and async/await
- Optional chaining
- Classes and class-based examples
- Date operations
- Promises and asynchronous behavior
- Shallow vs deep copy
- JSON stringify / parse
- A simple todo app
- A small backend demo using Express

## Task List

### 1. Data Copy Examples

- `datacopy.js` — demonstrates shallow copying with the spread operator.
- `datacopy2.js` — demonstrates creating a modified copy of an object and keeping the original unchanged.

### 2. Error Handling

- `errorhandling.js` — demonstrates `try/catch` usage and logging error details.

### 3. Fetch API

- `fetchapi.js` — fetches data from JSONPlaceholder and logs the response.
- It also includes an `async/await` example for consuming the API response.

### 4. Optional Chaining

- `optionaldemo.js` — shows how to safely access a missing property using optional chaining.

### 5. Classes

- `class-demo/classdemo.js` — demonstrates class creation, object instantiation, and methods.
- `class-demo/library.js` — contains a library-style class example with methods for borrowing, returning, and listing books.

### 6. Date Handling

- `date handson/datecreation.js` — shows how to create a date and extract year, month, day, and time values.
- `date handson/dateconversion.js` — demonstrates date comparison and validation.
- `date handson/datedemo.js` — demonstrates date difference calculations.

### 7. Promises and Async Behavior

- `promises/synch.js` — demonstrates async timing behavior with `setTimeout`.
- `promises/synchdemo.js` — shows synchronous vs asynchronous execution order.
- `promises/asynch-await.js` — demonstrates a Promise and `async/await` usage.

### 8. Shallow and Deep Copy

- `shallow-deep/shallow.js` — demonstrates how a shallow copy still shares nested objects.
- `shallow-deep/deepcopy.js` — demonstrates a deep copy using `structuredClone()`.
- `shallow-deep/json.js` — demonstrates converting a JavaScript object to JSON and back to an object.

### 9. Todo App

- `todo-app/task.js` — stores tasks and provides add, get, and complete functions.
- `todo-app/validator.js` — validates task title, priority, and due date.
- `todo-app/app.js` — simulates adding, listing, and completing tasks.

### 10. Backend Demo

- `backenedemo1/server.js` — Express server with CRUD routes for users.
- `backenedemo1/userapi.js` — router-based user API.
- `backenedemo1/package.json` — defines the Express dependency and start script.

## How to Run the Demos

### Root-level demos

Run these from the repository root:

```bash
node datacopy.js
node datacopy2.js
node errorhandling.js
node fetchapi.js
node optionaldemo.js
```

### Class demos

```bash
node class-demo/classdemo.js
node class-demo/library.js
```

### Date demos

```bash
node "date handson/datecreation.js"
node "date handson/dateconversion.js"
node "date handson/datedemo.js"
```

### Promise demos

```bash
node promises/synch.js
node promises/synchdemo.js
node promises/asynch-await.js
```

### Shallow / deep copy demos

```bash
node shallow-deep/shallow.js
node shallow-deep/deepcopy.js
node shallow-deep/json.js
```

### Todo app

```bash
node todo-app/app.js
```

### Backend demo

```bash
cd backenedemo1
npm install
npm start
```

After starting the backend, you can test the routes using your browser or an HTTP client.

## Notes

- The examples are intended as practice and demonstration files.
- The backend demo uses Express and exposes user-related routes.
- The README is meant to serve as a quick reference for all of the tasks completed in this workspace.
