# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook. The bug arises from an incomplete dependency array, leading to an infinite loop.

## Bug Description
The `useEffect` hook is used to perform side effects after a component renders.  However, if the dependency array is missing a value that changes within the effect, it will run continuously, causing performance issues or crashes.

## How to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the counter continuously incrementing, indicating the infinite loop.

## Solution
The solution involves adding the `count` variable to the dependency array to fix the infinite loop.

## Contributing
Feel free to contribute by creating pull requests and resolving any issues found!