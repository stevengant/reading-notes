# Class 36 Reading

## Dan Abramov Redux Tutorials

[Egghead.io - Fundamentals of Redux Course from Dan Abramov](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)
1. What is the first principle of Redux?
    - No matter the complexity or size of your application, you will present the whole state of your application as a single JavaScript object.

2. What is a store and what do we use our reducers for within that store?
    - A Redux store is a JavaScript object that holds the state of your application

3. Name three Redux store methods given to us by createStore and describe their use.
    - `getState()` method is used to retrieve curent state of the Redux store
    - `dispatch(action)` method is used to dispatch actions to all of the reducers in the store
    - `subscribe(listener)` method is used to subscribe a listener function to the REdux store. Whenever an action is dispatched, the listener function is called

4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.
    - `combineReducer()` combines multiple reducers into a single reducer function. It basically helps to keep your code organized and modular.