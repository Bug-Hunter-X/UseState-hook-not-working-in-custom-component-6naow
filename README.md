# Next.js useState Hook Error

This repository demonstrates a common error encountered when using the `useState` hook in custom components within a Next.js application.  The issue arises when the `useState` hook is not imported correctly, leading to the error "useState is not defined".

## Bug Description

The `useState` hook, crucial for managing component state in React, is not available within the `MyComponent` component. This results in a runtime error.

## Solution

The solution involves importing the `useState` hook from 'react'. The corrected code is provided in the `bugSolution.js` file. 
