# ReactFacts site

This project is part of the Scrimba [React](https://scrimba.com/learn/learnreact) course.

## About The Project

<img src='https://user-images.githubusercontent.com/69361901/197352649-d7c73a5c-9171-45a2-94ac-7f3be1c272b8.png' alt='ReactFacts screenshot' width='500px' text-align='center'>

Live Site: https://reactfacts-by-alphfonti.netlify.app/

## What I learned in this project

- React (composable and declarative)
- JSX syntax (must import it to be able to used it)
- ReactDOM (must import it to be able to used it)
- Custom components
- Parent and children components


1. Why do we need to `import React from "react"` in our files?
React is what defines JSX

2. If I were to console.log(page) in index.js, what would show up?
A JavaScript object. React elements that describe what React should
eventually add to the real DOM (UI elements) for us.

3. What's wrong with this code:
```
const page = (
    <h1>Hello</h1>
    <p>This is my website!</p>
)
```
We need our JSX to be nested under a single parent element

4. What does it mean for something to be "declarative" instead of "imperative"?
Declarative means I can tell the computer WHAT to do 
and expect it to handle the details. Imperative means I need
to tell it HOW to do each step.

5. What does it mean for something to be "composable"?
We have small pieces that we can put together to make something
larger/greater than the individual pieces.

6. What is a React component?
A function that returns React elements.

7. What's wrong with this code?
```
function myComponent() {
    return (
        <small>I'm tiny text!</small>
    )
}
```

We need the name of the component in PascalCase (MyComponent)

8. What's wrong with this code?
```
function Header() {
    return (
        <header>
            <nav>
                <img src="./react-logo.png" width="40px" />
            </nav>
        </header>
    )
}

ReactDOM.render(header(), document.getElementById("root"))
```

We need to create a new instance of a component by putting the name inside brackers `<Header() />`. 

Parent and children components

## Mental outline

<img width="500" alt="image" src="https://user-images.githubusercontent.com/69361901/197352914-9175c6d6-563f-4d0c-8b31-53a94409dd3a.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/69361901/197352915-af49f0bb-6b98-4303-95e7-984878e142eb.png">

## What do I need to run React in my computer

<img width="400" alt="image" src="https://user-images.githubusercontent.com/69361901/197352917-6b84dd4f-5936-4d09-9242-a3da1969fa79.png">

<img width="500" alt="image" src="https://user-images.githubusercontent.com/69361901/197352918-caeaca08-a489-46c3-88c0-c2ef195aef3c.png">

## Built with 

- [React](https://reactjs.org/)

## Acknowledgements

- [Bob Ziroll](https://github.com/bobziroll)
