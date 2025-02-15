# React Native: undefined is not an object (evaluating 'this.state.myData')

This repository demonstrates a common React Native error: 'undefined is not an object (evaluating 'this.state.myData')'. This occurs when trying to access component state before it has mounted.  The `bug.js` file shows the problematic code. The solution in `bugSolution.js` utilizes the `useEffect` hook to ensure state is accessed only after the component has mounted and its state is fully initialized. 

## How to Reproduce
1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` or `npx react-native run-ios`.
5. Observe the error in the `bug.js` example.
6. Compare with the corrected version in `bugSolution.js`.