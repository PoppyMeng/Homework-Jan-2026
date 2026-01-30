1. How do we do prop types check?
Prop types can be checked using the PropTypes library, which performs runtime type checking for React props. In modern applications, TypeScript is preferred because it provides compile-time type safety and better developer tooling.

2. What is Prop drilling?
Prop drilling is the process of passing props through multiple component layers to reach a deeply nested component. It can make code harder to maintain and is often solved using Context API or state management libraries.

3. How are we going to render a variable as a React component?
You can assign a component to a variable and render it using JSX syntax. React treats the variable as a component as long as it starts with a capital letter.

4. What is HOC and why do we need it?
A Higher-Order Component (HOC) is a function that takes a component and returns a new component with added behavior. It’s used to reuse component logic, though hooks are now the preferred approach.

5. How to properly render an SVG element as a React component?
SVGs can be imported as React components using bundler support (e.g., import { ReactComponent as Icon } from './icon.svg'). This allows SVGs to be treated like normal components with props.

6. What is lazy loading and what does it help?
Lazy loading defers loading components until they are actually needed. It improves initial load performance and reduces bundle size.

7. List several React hooks that you use most and what do they do
Common hooks include useState for local state, useEffect for side effects, and useContext for accessing shared state. Others like useMemo and useCallback help optimize performance.

8. What is useState and what value should we pass in?
useState is a hook for managing local component state. The initial value should match the expected state type, such as a number, string, array, or object.

9. What is the hook useEffect and why do we need it?
useEffect is used to handle side effects like data fetching, subscriptions, or DOM updates. It runs after render and helps separate side-effect logic from rendering logic.

10. What is the dependency array in useEffect?
The dependency array controls when the effect runs. The effect re-runs whenever one of the listed dependencies changes.

11. What is the lifecycle method componentDidUpdate equivalent hook?
useEffect with dependencies acts as the equivalent of componentDidUpdate. It runs whenever the specified dependencies change.

12. What is the lifecycle method componentDidMount equivalent hook?
useEffect with an empty dependency array ([]) is equivalent to componentDidMount. It runs once after the component is first rendered.

13. What is the lifecycle method componentWillUnmount equivalent hook?
A cleanup function returned from useEffect is equivalent to componentWillUnmount. It runs just before the component is removed from the DOM.

14. What’s the difference between useCallback and useMemo?
useCallback memoizes functions, while useMemo memoizes computed values. Both help prevent unnecessary re-renders and expensive recalculations.

15. What is useContext and the difference between useContext and useState?
useContext allows a component to consume values from React Context without prop drilling. useState manages local component state, while useContext accesses shared state provided by a Context Provider.


