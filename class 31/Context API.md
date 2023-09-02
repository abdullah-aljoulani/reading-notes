## Context API

**Summarize the five principles for structuring state**

1-Single Source of Truth.
2-State Is Read-Only.
3-Changes Are Made with Pure Functions.
4-Data Flow in One Direction.
5-Isolation of State.

**What problem do Contexts aim to solve?**

Contexts in React aim to solve the problem of "prop drilling," which occurs when you need to pass data through multiple levels of nested components. Instead of manually passing props down the component tree.

**What is one technique to try before useContext?**

One technique to try before using useContext is to use the "prop drilling" approach, where you pass the required data as props through each intermediate component in the component tree.

**What hook complements useContext for complex applications?**

The useReducer hook complements useContext for complex applications. useReducer allows you to manage state changes using a reducer function, which is well-suited for handling complex state logic.
