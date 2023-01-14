# Read: Class 03 Passing Functions as Props

## React Docs - Lists and Keys

1. What does .map() return?
\
The function .map() calls a function for each item of an array returns a new array with the results.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
\
In React, elements can be displayed by using courly braces.
3. Each list item needs a unique ____.
\
component
4. What is the purpose of a key?
\
The purpose of a key is to give elements inside an array an identity.

## The Spread Operator

1. What is the spread operator?
\
The spread operator is used with three dots (...) to expand an object into the list of arguments.
2. List 4 things that the spread operator can do.
\
The spread operator can use math functions, use an array as arguments, combine objects, and add to state in React.
3. Give an example of using the spread operator to combine two arrays.
\
    const red = [`🍒`,`🍓`,`🍎`]

    const green = [`🥝`,`🍐`,`🍈`]

    const fruits = [...myArray,...yourArray]

    return fruits

This will return 🍒 🍓 🍎 🥝 🍐 🍈.

4. Give an example of using the spread operator to add a new item to an array.
\
    const animal = ['🐸','🐻','🐰']

    const manyAnimals = ['🐻‍❄️', '🐋', ...animal]

This will return ['🐻‍❄️', '🐋', '🐸','🐻','🐰']
5. Give an example of using the spread operator to combine two objects into one.
\
    const red = {red: "🍒🍓🍎"}

    const green = {green: "🥝🍐🍈"}

    const redgreen = {...red,...green}
    return redgreen

This will return { red: "🍒🍓🍎", green: "🥝🍐🍈"}

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
\
The first step the developer does is create the function where the state that is going to be changed.
2. In your own words, what does the increment function do?
\
The increment functions increses the state by 1.
3. How can you pass a method from a parent component into a child component?
\
You can pass a method from a parent component into a child by referring to the object using this.
4. How does the child component invoke a method that was passed to it from a parent component?
\
The child componenet can invoke a method by calling the method that changed the state.
