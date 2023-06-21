"# useComponentDidUpdate-react-hook"
Use the useRef() hook to create a variable, mounted, that tracks if the component has been mounted.
Use the useEffect() hook to set the value of mounted to true the first time the hook is executed.
Run the provided callback on subsequent hook executions.
Providing a dependency array for the second argument, condition, will only execute the hook if any of the dependencies change.
Behaves like the componentDidUpdate() lifecycle method of class components.
