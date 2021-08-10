# Forms and JS Events

## Forms

HTML borrows the concept of a form to refer to different 
elements that allow you to collect information from visitors to 
your site.
Whether you are adding a simple search box to your website or 
you need to create more complicated insurance applications, 
HTML forms give you a set of elements to collect data from 
your users

### Form Structure

**< form>**

Form controls live inside a < form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

**action**

Every < form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted

**method**

Forms can be sent using one of two methods: get or post. With the get method, the values from the form are added to the end of the URL specified in the action attribute

![form](https://i1.wp.com/www.csscodelab.com/wp-content/uploads/2020/01/fancy-text-input-form-html-css.png?fit=1159%2C709&ssl=1)



## JavaScript Events

HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

Event handlers can be used to handle and verify user input, user actions, and browser actions:

* Things that should be done every time a page loads
* Things that should be done when the page is closed
* Action that should be performed when a user clicks a button
* Content that should be verified when a user inputs data


Many different methods can be used to let JavaScript work with events:

* HTML event attributes can execute JavaScript code directly
* HTML event attributes can call JavaScript functions
* You can assign your own event handler functions to HTML elements
* You can prevent events from being sent or being handled

![Events](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events-1200x720.png)