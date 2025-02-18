# React Native TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications: the `TypeError: Cannot read properties of undefined (reading 'property')` error. This error occurs when attempting to access a property of an object that is currently undefined or null.  This often happens when dealing with asynchronous operations, where data might not be available immediately during rendering.

The `bug.js` file showcases the problematic code.  The `bugSolution.js` file provides a corrected version using optional chaining and nullish coalescing to handle the potential for undefined or null values gracefully.

## Setup

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the app.