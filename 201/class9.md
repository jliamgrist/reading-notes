# HTML Web forms — Working with user data

+ Readability/understanding of what the input should be or what the form is asking for.
+ Simplicity
+ Accessibility
+ Formatting
+ Overall UX

Some form elements are:

+ Text input field - allows for multiple lines of text as input
+ Submit button - sends form data to a server
+ Password field - hides sensitive password, can add validation
+ Drop down - offers multiple choice
+ Checkbox/radio button - offers selectability

How would you describe events to a non-technical friend?
When using the addEventListener() method, what 2 arguments will you need to provide?
Describe the event object. Why is the target within the event object useful?
What is the difference between event bubbling and event capturing?

Events in JS are actions that trigger some result. Similar to pressing the power button on a remote, a TV can then turn on because a signal is sent, which can then be read by the TV. 

When using the addEventListener() method, we can pass two parameters.

+ one to indicate what the event should listen for, that we want to listen to the click event
+ the second param to call to a function, declaring what the event should do when it is triggered

An event object is a parameter that helps send extra information to the handler. The target within an event object lets the handler know what specifically to target - for example targeting a change in a specific element, instead of an entire page. 

Event bubbling describes how the browser handles events targeted at nested elements. Events are fire fist on the innermost element targeted, then on subsequent less nested elements. Event capture is differend and needs to be declared as an attribute with a boolean. The event capture first fist on the least nexted element, then subsequently on more nexted elements until the target is reached.
