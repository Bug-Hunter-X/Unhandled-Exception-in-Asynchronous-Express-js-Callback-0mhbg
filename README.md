# Unhandled Exception in Asynchronous Express.js Callback

This repository demonstrates a common error in Node.js Express applications: unhandled exceptions within asynchronous callbacks.  The code simulates an asynchronous operation that randomly throws an error, causing the server to crash without proper handling.

The `bug.js` file contains the flawed code.  `bugSolution.js` provides a corrected version with robust error handling.

## How to Reproduce

1. Clone the repository.
2. Run `npm install express` to install the required dependency.
3. Run `node bug.js`. Observe that the server will crash intermittently.
4. Run `node bugSolution.js`. This version demonstrates the solution and will not crash.