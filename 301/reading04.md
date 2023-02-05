# Read: Class 04 React and Forms

## Forms

1. What is a ‘Controlled Component’?\
A controlled component is an inpput form element whose value is controlled by React.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.\
We should update the state as soon as the response is entered because there si a value attribute set up in the form element.
3. How do we target what the user is entering if we have an event handler on an input field\
We can target what the user is entering by adding a name attribute to each element (event.target.name).

## The Conditional (Ternary) Operator

1. Why would we use a ternary operator?\
We would use the ternary operator to write an if statement in just one line of code.
2. Rewrite the following statement using a ternary statement:\
    if(x===y){\
  console.log(true);\
    } else {\
  console.log(false);\
    }\

x === y ? 'true' : 'false'
