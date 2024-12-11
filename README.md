# React Native: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native: 'Cannot read properties of undefined (reading 'property')'.  This error occurs when trying to access a property of an object that is null or undefined, often during asynchronous data fetching.  The example shows how to reproduce the error and how to fix it using optional chaining and nullish coalescing.

## Reproducing the Error

The `bug.js` file contains the erroneous code.  Run the app and you will observe the error in the console.

## Solution

The `bugSolution.js` file demonstrates a corrected approach using optional chaining (`?.`) and the nullish coalescing operator (`??`). This ensures that the code gracefully handles cases where the data is not yet available.

## How to run

1. Clone the repository: `git clone <repo_url>`
2. Navigate to the directory: `cd react-native-undefined-property`
3. Install dependencies: `npm install` or `yarn install`
4. Run the app: `npx react-native run-android` or `npx react-native run-ios`