# React Router v6 Nested Route Parameter Issue

This repository demonstrates a common issue encountered when using nested routes with parameters in React Router v6.  The problem occurs when a route parameter is present but not properly handled within the nested route structure, leading to unexpected behavior such as the component failing to render or display incorrect data.

The `bug.js` file contains the buggy code, while `bugSolution.js` offers a corrected implementation.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `npm start` to start the development server.
4. Navigate to `/users/123`.  Observe that the User component does not render correctly or throws an error.

## Solution

The solution involves ensuring proper use of the `useParams` hook within the nested route component to access the route parameters correctly. The corrected code is in `bugSolution.js`.