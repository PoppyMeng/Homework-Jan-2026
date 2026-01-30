1. What is the Flux architecture?
Flux is an application architecture that enforces one-way data flow. Data moves from actions to a central store and then to the view, making state changes predictable.

2. Explain what the Redux store, actions, reducers are and what they do.
The store holds the entire application state in a single object. Actions are plain objects that describe what happened, and reducers are pure functions that update the state based on those actions.

3. Describe the workflow of Redux.
A component dispatches an action describing a change. The reducer processes the action and returns a new state, which updates the store and re-renders subscribed components.

4. How do you create/configure a store in Redux?
A store is created using configureStore (or createStore in older Redux) by passing in reducers and middleware. The store is then provided to the app using the <Provider> component.

5. Explain how to use connect()
connect() is a higher-order function from react-redux that connects a React component to the Redux store. It maps state and dispatch to component props.

6. What is mapDispatchToProps and what does it do?
mapDispatchToProps maps dispatch actions to component props. It allows components to trigger state changes without directly calling dispatch.

7. What is mapStateToProps and what does it do?
mapStateToProps selects the parts of the Redux state that a component needs. It ensures the component re-renders when the selected state changes.

8. How do we use useSelector and useDispatch?
useSelector reads data from the Redux store, while useDispatch returns the dispatch function. These hooks replace connect() and make Redux usage simpler in function components.
