# Week 7

This week we learned about Components, Props, and States. We learned when to use Functional Components vs Class Components, the former being used for mostly static data, for example simply displaying a welcome message or text,  the latter is used when adding actual logic and access/modify the state, for example when dynamic content is being loaded or created on page load.

Properties are part of React, and are essentially values that are passed down between components, these values aren't modified but are used in the logic of the child component when needed.

We also learned about the various lifecycles of a component within React. These lifecycles fall into 3 different categories: Mounting, Updating and Unmounting. Lifecycle methods are the integrated methods that are executed at various stages of a component's life. The most common lifecycle method being `render()`, which is required within a class. Other methods include `componentDidMount()` which is called once the component is ready, `componentDidUpdate()`, which occurs whenever something was updated, such as the state, and `componentWillUnmount()` which of course is executed when the component is about to be destroyed.

These methods can be used to implement various functionalities in your app, and are useful because you know exactly when they will be called.

For me these make a lot of sense because, as a user of the Unity3D game engine, similar functions are available that are called at specific times in a script's life, for example `Awake()` which is called as soon as the script is loaded, which is comparable to `componentDidMount()`.