# Read: Class 05 Putting it all Together

## React Docs

1. What is the single responsibility principle and how does it apply to components?\
The single responsibility priciple is a technique where each componenet should do one thing. Each functionality in your webpage should be separated into its own component.
2. What does it mean to build a ‘static’ version of your application?\
Building a 'static' version of your application means to build a version of your application that renders the user interface but has no interactivity.
3. Once you have a static application, what do you need to add?\
Once a static applicationnis built, state needs to be added.
4. What are the three questions you can ask to determine if something is state?\

- It is passed in from a parent using props?
- Does it remain unchanged over time?
- Can you compute it based on any other state or props in your component?

5. How can you identify where state needs to live?\
You can identify where the state need to live by finding the component that owns the state.

## Higher-Order Functions

1. What is a “higher-order function”?\
A "higher-order function" is a functions that operate on other functions.
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?\
Line 2 of the greaterThan function is returning a new function that shows true or false depending on what number is put in.
3. Explain how either map or reduce operates, with regards to higher-order functions.\
Reduce creates a value by taking a single element from an array and adding it to the current value. The sum or combination of all these elements is the value created by reduce.
