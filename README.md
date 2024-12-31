# React Router v6 - Missing 404 Route
This repository demonstrates a common error in React Router v6:  missing a route to handle 404 (Not Found) errors.  When navigating to a URL that doesn't match any defined routes, the application may render nothing or show unexpected behavior.

The `App.js` file shows the incorrect implementation, while `AppSolution.js` provides the solution.

## How to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to a URL that doesn't exist (e.g., `/invalid-path`).

You'll notice in `App.js` that there's no route to handle such cases, leading to an undesirable user experience.  `AppSolution.js` fixes this.