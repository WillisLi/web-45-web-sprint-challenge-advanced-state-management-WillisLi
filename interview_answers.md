# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    Context API allows us to share values between components without have to directly write each prop.
2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Store contains the state of the application, reducers allow us to create a pure function without side-effects and manage our states in a predictable manner, and actions contain an action type and any relevant data. Stores are know as the single source of truth because they reveal the state of the application. All we care about is being able to compare what is currently in the state and what was there previously when debugging.
3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    Redux Thunk allows us to make the reducer flow asynchronous and make API calls in our action creators.
4. What is your favorite state management system you've learned and this sprint? Please explain why!
    Redux because it is convenient being able to know the current and previous states when testing out reducers and API calls.