### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
React is a JavaScript library for building user interfaces, particularly single-page applications where you need a fast, interactive, and dynamic user experience. Component based coding makes large prjects manageable allows for dom to update on parts that need updating and lots of exisitng libraries to build projects in a flexible manner
- What is Babel?
Babel is a JavaScript compiler that allows you to write next-generation JavaScript code and convert it to backward-compatible versions for current and older browsers or environments.
- What is JSX?
JSX is a syntax extension for JavaScript that looks similar to HTML or XML and is used with React to describe what the UI should look like
- How is a Component created in React?
A component in React can be created either as a function component or a class component.


function MyComponent(props) {
  return <div>Hello, {props.name}!</div>;
}

- What are some difference between state and props?
Props: Short for properties, props are read-only data passed from parent to child components. immutable

stateState is mutable and local to the component it is defined in. It holds information that may change over the lifecycle of the component and can be updated using setState. mutable
- What does "downward data flow" refer to in React?
Downward Data Flow means that data in React flows from parent components to child components. 
- What is a controlled component?
A Controlled Component is a form element and input that is controlled by react state
- What is an uncontrolled component?
maintains own state uses href to access value doesnt rely on react state
- What is the purpose of the `key` prop when rendering a list of components?
The key prop is used by React to identify which items have changed, been added, or removed in a list of elements
- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
unnecessary re-renders and incorrect behavior since the index may not uniquely identify an element across renders performance issues
- Describe useEffect.  What use cases is it used for in React components?
useEffect is a React hook that allows you to perform side effects in function components. It runs after the render and can be used for various tasks such as data fetching
- What does useRef do?  Does a change to a ref value cause a rerender of a component?
useRef is a React hook that returns a mutable ref object whose .current property can be used to store a value or reference to a DOM element
- When would you use a ref? When wouldn't you use one?
manage playbacks, access dom storing mutable value wouldnt use to communicate between props or update values
- What is a custom hook in React? When would you want to write one?
 Custom hooks enable you to share logic without duplicating code or restructuring your component hierarchy.
 When you have stateful logic that needs to be reused across multiple components