# University Course Management System

Web Programming - Assignment 3 implementation demonstrating Asynchronous Callbacks, ES6 Classes, Object Property Descriptors, and Higher-Order Functions.

## File Organization

- **`models.js`**: Defines the `Student` class and enforces immutable `id` property using `Object.defineProperty()`.
- **`database.js`**: Simulates an asynchronous data fetch from a server using `setTimeout` and callback pattern.
- **`analytics.js`**: Houses utility functions for computing averages, identifying the top student using `.reduce()`, and generic filtering via HOF.
- **`main.js`**: The main execution file that orchestrates data fetching, instantiates models, tests immutability, and logs the report.

## How to Run

1. Ensure Node.js is installed.
2. Verify `"type": "module"` is configured in your `package.json`.
3. Execute the script:
   ```bash
   node main.js
