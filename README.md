# Express.js - Missing Request Body Parameter Handling

This repository demonstrates a common error in Express.js applications: unhandled errors when request body parameters are missing.  The `bug.js` file shows the problematic code, where the application attempts to access properties from the request body without checking for their existence.  This can lead to unexpected crashes and errors.

The `bugSolution.js` file provides a solution by adding robust error handling to check for the existence of required parameters before accessing them.  This ensures that the application gracefully handles situations where the request body is malformed or incomplete.