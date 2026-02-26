# REACT JS INTERVIEW QUESTIONS



### &nbsp;---JavaScript \& React Essentials---



**What is Object Oriented Programming?**

**What is "this" keyword in JS?**

&nbsp;   - "this" keyword in JavaScript refers to the object that is currently executing the code.

&nbsp;   - Arrow functions do not have their own "this" binding. They inherit the "this" value from the surrounding scope where they are defined.

&nbsp;   - The call(), apply(), and bind() methods can be used to explicitly set the value of this when calling a function.

**What are call(), apply() \& bind() in JavaScript?** 

&nbsp;   - Methods that allow you to control the "this" value within a function, which is the context in which a function is executed.

&nbsp;   - They are useful for manipulating the object to which "this" refers, enabling function borrowing and code reuse.

&nbsp;   - call and apply invoke the function immediately, while bind returns a new function that can be invoked later.

&nbsp;   - call accepts arguments individually, while apply accepts an array of arguments.

DOM \& Virtual DOM 

Undefined value vs Null value 

Class based \& Functional components 

Constructors \& their usage in class based \& functional components 

What are arrow functions and why are they used?

###### Component lifecycle 

&nbsp;   **Class Based Components**

&nbsp;       - componentDidMount()

&nbsp;       - componentDidUpdate()

&nbsp;       - componentWillUnmount()

    **Functional Components**

&nbsp;       - useEffect() \& cleanup

**Controlled \& Uncontrolled components** 

&nbsp;   - Controlled use React's state to store and update form input values

&nbsp;       Suitable for dynamic forms, real-time validation, and situations where tight control over input values is necessary.



&nbsp;   - Uncontrolled allow the DOM to handle input values directly.

&nbsp;       Ideal for simpler forms where the focus is on a straightforward implementation

What is event looping?



### ---React Essentials---

Why should we use React? 

Advantages \& Limitations of React 

**What are the core components of React JS?**

&nbsp;   1.Components (Functional \& Class)

&nbsp;   2. JSX

&nbsp;   3. Virtual DOM

&nbsp;   4. Props

&nbsp;   5. State

&nbsp;   6. React Hooks

&nbsp;   7. Lists (array, array of objects etc)

&nbsp;   8. Forms (text fields, checkboxes \& dropdowns)

Fragments 

JSX files vs JS files 

TypeScript vs JavaScript 

**What are Higher Order Components(HOC)?**

&nbsp;   Function that takes a component as an argument and returns a new, enhanced component.

**Refs \& Portals**

&nbsp;   - Refs in React provide a way to access DOM elements or React elements directly via useRef() hook.

### ---Hooks---



**useState** 

&nbsp;   - Usd to handle data in a component

**useEffect** 

&nbsp;   - Performs side effects like data fetching, subscriptions, or DOM manipulations after rendering.

**useCallback** 

&nbsp;   - Memoizes (caches) callback functions to prevent unnecessary re-renders of child components.

**useMemo** 

&nbsp;   - Memoizes the result of expensive computations, caching the results and only recalculating when dependencies change.

**useReducer**

&nbsp;   - Can be used when state updates depend on the previous state, instead of useState()

**useRef**

&nbsp;   - Used to create refs

**useFetch**

&nbsp;   - Fetch data from a specified URL using the fetch API and provides a consistent pattern for handling loading, success, and error states.

**useLayoutEffect**

&nbsp;   - Similar to useEffect, but it fires synchronously after all DOM mutations, before the browser renders.

**Custom Hooks**



### ---State Management---



State vs Props

Prop drilling \& how to avoid it - Using Context API, Redux 

Lifting State up 

Context API 

Redux 

Redux Toolkit 

Redux Slices 

useSelector \& useDispatch hooks

Difference between useReducer hook \& Reducer (Redux)

Redux Thunk 

Redux Saga 

Action \& Reducers 



### ---Additional Concepts---



**What is async-await?** 

&nbsp;   - Waiting for the response \& resuming code execution upon receiving the response

**What are Promises?** 

&nbsp;   - Objects that represent eventual completion (Fulfilled or Rejected) of an asyncronous operation \& its value

&nbsp;   - Pending, Fulfilled \& Rejected states

**Function closures** 

&nbsp;   -When an outer function is called, it creates a scope for its variables. When an inner function is defined within the outer function, it forms a closure. The closure captures the outer function's scope, allowing the inner function to access the outer function's variables. Even after the outer function has completed, the closure retains access to these variables.

&nbsp;   - Data encapsulation \& persistence

**Join** (array.join(separator)) 

Client side vs Server side rendering 

**How to prevent re-rendering in React?** - useCallback, useMemo 

**How to prevent infinte loops?** - Dependency Array in useEffect, don't call func in useEffect \& dependency array 

React Router

What is lazy loading? How to implement it?

REST API - Advantages \& Disadvantages

GraphQL - Advantages \& Disadvantages

GraphQL vs REST API

Axios

