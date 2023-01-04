HTML

1. Why are forms so important in web development?
They're used mostly for collecting data from users or allowing them to control a user interface.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
It's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

3. List 5 form elements and explain their importance.

<form>    Defines an HTML form for user input
<input>    Defines an input control
<textarea>    Defines a multiline input control (text area)
<label>    Defines a label for an <input> element
<fieldset>    Groups related elements in a form

(<https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form>).
(<https://www.w3schools.com/html/html_form_elements.asp>).

JS

1. How would you describe events to a non-technical friend?
Events interactions that happen in the system but need information from that same system to run.

2. When using the addEventListener() method, what 2 arguments will you need to provide?
Inside the addEventListener() function, we specify two parameters: the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.

3. Describe the event object. Why is the target within the event object useful?
 The event object is automatically passed to event handlers to provide extra features and information.

4. What is the difference between event bubbling and event capturing?
Bubbles up from the innermost element that was clicked. Capturing from the outermost element that was clicked.

(<https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#using_addeventlistener>).
