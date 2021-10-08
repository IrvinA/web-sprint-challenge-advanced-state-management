# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    Context API helps solve the problem of prop drilling on all levels of components.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    Actions are all the functions that a component requires, including the action objects that define an action.
  Reducers are all data that deal with the creation or change of the data held within state. Things like initial state and which state are affect by which action are defined here.
  Store is a centralized location that contains all the information defined by our reducers and actions that is then accessible to our entire document.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Thunk allows us to return functions, which allows us to work with asynchronous actions.
  This means that our action creators can be returned as functions which can allow us to dispatch them with a delay or after certain conditions have been met.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    My favorite system has been redux. I enjoy not having to worry about drilling props into my components and having all my data sorted neatly into its appropriate logic folders.