# React useEffect Infinite Render Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The bug is caused by an incorrect dependency array, leading to an infinite render loop.  The solution showcases the correct usage of the dependency array to resolve this issue.

## Bug

The `bug.js` file contains a React component with an `useEffect` hook that has a missing dependency in the dependency array. This causes the effect to re-run on every render, creating an infinite loop.

## Solution

The `bugSolution.js` file provides the corrected version of the component with a correctly specified dependency array. The effect now only runs when the relevant data changes, preventing the infinite loop.

## How to run

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.  The application will then be accessible in your browser.