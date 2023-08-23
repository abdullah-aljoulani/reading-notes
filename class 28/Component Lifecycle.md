## Component Lifecycle

**What is the main intended use case for the useEffect hook?**

The main intended use case for the useEffect hook in React is to manage side effects within functional components. Side effects are actions or behaviors that occur in a component other than rendering the user interface.

**How does the effect’s logic interact with the component?**

The effect's logic in the useEffect hook interacts with the component by allowing you to perform side effects at specific points in the component's lifecycle. It provides a structured way to incorporate behaviors that are not directly related to rendering the UI

**What is the importance of the return value from the effect’s logic function?**

1- Resource Cleanup: Side effects often involve allocating resources, such as setting up event listeners, starting timers, or opening network connections.

2- Preventing Dangling References: Without a cleanup function, resources established by the effect's logic might persist even after the component unmounts or when the effect is re-run due to updates.

3- Efficient Updates: When the component updates and the effect runs again, the previous cleanup function is executed before the new effect logic is run
