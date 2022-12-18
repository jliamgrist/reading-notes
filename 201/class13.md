# Class 13

## Local Storage 

The web is stateless, meaning if you close a web application and then re-open it, the state will be reset. 

You can save a user's state by matching their inputed username but this only works if they have submitted credentials and signed up with the application. 

Cookies can store information that can be read by the website and return user info such as the "state". But another way we now have is to save to local storage with HTML5. 

You can use the `setItem()` and `getItem()` methods. 

`localStorage.setItem('favoriteflavor','vanilla');

If you read out the favoriteflavor key, you will get back “vanilla”:

`var taste = localStorage.getItem('favoriteflavor');
// -> "vanilla"`

HTML5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser.

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Data is stored as a string, so it needs to be retrieved as a string and if needed, converted to a boolean, integer, etc.