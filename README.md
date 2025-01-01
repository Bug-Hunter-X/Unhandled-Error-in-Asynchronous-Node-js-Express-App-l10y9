# Unhandled Error in Asynchronous Node.js Express App

This repository demonstrates a common error in Node.js applications: unhandled errors within asynchronous callbacks.  The `bug.js` file contains an Express.js server that simulates an asynchronous operation.  Half of the time, it throws an error, which is not caught, leading to a crash. The `bugSolution.js` demonstrates how to properly handle such errors using `try...catch` blocks or Promises.