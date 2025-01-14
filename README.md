# Unnecessary useEffect Re-renders in React

This example demonstrates a common React bug where the `useEffect` hook causes unnecessary re-renders and console logs.  The `useEffect` hook is called after every render, including the initial render. This can lead to performance issues and unnecessary side effects. 

The solution shows how to optimize the `useEffect` hook to only run when the count changes.