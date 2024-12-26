# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers:  missing error handling for invalid input.

The `bug.js` file shows an example of a route handler that does not handle the case where the user ID is not a valid integer. This can lead to unexpected errors and crashes.

The `bugSolution.js` file provides a corrected version of the route handler that includes proper error handling.