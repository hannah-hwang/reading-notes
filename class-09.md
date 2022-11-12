# Read: Class 09 Forms and JS Events
## HTML Forms
1. Forms are important in web development because they are powerful tools for interacting with and collecting data from users. They are one of the main points of interaction between a user and a web page.
2. Some key things to keep in mind about user experience when designing a form are to keep it simple and focused, and to explicitly label each form element.
3. 5 form elements are:
    - \<input>: used to display many different kinds of prompts that require an input of some sort; what is displayed is defined by the type attirbute
    - \<form>: container element which defines the form; everything you want in the form shoule be put in here
    - \<label>: names or adds a caption to an item; associates label to the input
    - \<textarea>: adds an input field which allows a user to type in a textbox
    - \<button>: adds a button which can be used to submit the data written in the form

## JavaScript Events
1. An event is an action that occurs in the programming system. When you do something in a web page, an event that corresponds to that action via code will happen.
2. 2 arguments needed when using the addEventListner() method are the name of the event and a function to handle the event.
3. The event object is a parameter that is automatically passed on to event handlers to provide extra information. The target property within the event object is useful because it refers to the element the event occurred upon.
4. The difference between event bubbling and event capturing is that in event bubbling, the browser looks to for the click event handler in the parent and moved outward until it reaches the outer-most ancestor (HTML), whiile in event capturing the click event handler runs from the outer-most ancestor until it gets to the parent.