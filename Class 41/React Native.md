## React Native

### getting started with react native

**Name three Core Components of React Native and describe what they do.**

1- Components: Components are the building blocks of a React Native application.
2- Props: Props, short for "properties," are a mechanism for passing data from parent components to child components in React Native.
3- State: State is a fundamental concept in React Native that allows components to manage and store data that can change over time.

**What problem does React Native solve (why call it native)?**

React Native is called "native" because it aims to solve the problem of building mobile applications that look and feel like they were developed using platform-specific (native) technologies, such as Swift for iOS and Java/Kotlin for Android.

1-Cross-Platform Development: One of the main problems React Native solves is cross-platform development.
2-Native-Like Performance: React Native bridges the gap between web development and native mobile development by providing a way to render components using native code.
3-Reusable Components: React Native encourages the creation of reusable components.

**What are the building blocks of a React Native app? How does that compare to a React app?**

1-Components: React Native applications are also built using React components.
2-Styling: React Native uses a similar styling approach to React, but with some differences.
3-Native Modules: React Native allows developers to access platform-specific functionality through native modules.

both React Native and React web apps share the core principles of using React components and a component-based architecture. However, React Native apps are specialized for mobile development and incorporate native components and modules for access to device-specific functionality, while React web apps are designed to run in web browsers and use web-specific technologies like HTML, CSS, and the DOM.

### expo

**What solution does expo provide?**

Expo is a free and open-source platform for building native iOS, Android, and web applications using JavaScript and React

1-Development Environment: Expo provides a development environment that includes a command-line interface (CLI) for initializing, developing, building, and deploying apps
2-Built-in Components and Libraries: Expo comes with a wide range of pre-built UI components
3-Expo Web: Expo also supports building web applications alongside mobile apps.

**Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.**

Managed Workflow

**What is the difference between React Native and Expo?**

React Native and Expo are two related but distinct frameworks for building mobile applications using JavaScript and React.
React Native offers more flexibility and control over the development process, making it suitable for complex or highly customized projects that require extensive native code modifications. On the other hand, Expo is designed to simplify development by abstracting away many native complexities, making it ideal for rapid development of standard mobile apps and web apps with less need for customization and native code integration.

**What does snack allow you to do?**

Expo Snack is a web-based code editor that empowers you to compose, preview, and distribute React Native code right within your web browser. It provides a user-friendly means to explore React Native without the requirement of configuring a development environment.

### ejecting

**What does “eject” mean within the context of Expo?**

In the context of Expo, "ejecting" refers to the process of transitioning an Expo-managed project into a standard React Native project. When you eject from Expo, you essentially detach your project from Expo's Managed Workflow and gain more control and flexibility over the project's native code and configuration.

**When should you not eject?**

you should avoid ejecting from Expo when the Managed Workflow meets your project's requirements, you value the simplicity and convenience it offers, and you don't have specific needs for custom native code or complex platform-specific integrations. Ejecting should be a deliberate decision based on your project's unique needs and your team's expertise in native mobile development.

**Why might you choose to eject?**

you should choose to eject from Expo when your project demands advanced native functionality, extensive customization, or access to platform-specific integrations that cannot be achieved within Expo's Managed Workflow.