# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    It helps solve the problem of having to prop drill.
2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions carry the information that needs to be stored, reducers are predictable functions that take the previous state to create a new one. Redux only uses one store and it is split up around the app, which is why its know as the 'single source of truth'
3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    It prevents from having to cause side effects, thunk allows action creators to return a function
4. What is your favorite state management system you've learned and this sprint? Please explain why!
    Context API cause I understood the code I was working with better rather than standard redux and having to prop drill down.