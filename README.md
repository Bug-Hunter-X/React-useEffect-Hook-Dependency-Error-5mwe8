# React useEffect Hook Dependency Error
This repository demonstrates a common error in React's `useEffect` hook: missing dependencies in the dependency array.

The `bug.js` file contains code with this error. The effect does not re-run when the count changes because `count` is not specified in the dependency array.  This leads to unexpected behavior and potential bugs.

The `bugSolution.js` file provides the corrected code with the correct dependencies in the dependency array.