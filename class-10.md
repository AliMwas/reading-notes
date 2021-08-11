# Debugging

Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

## JavaScript Debuggers
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.
The console.log() Method
If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:
![Debugging](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg?cb=1415345877)

**JavaScript try and catch**
The try statement allows you to define a block of code to be tested for errors while it is being executed.

The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

The JavaScript statements try and catch come in pairs:

try {

  Block of code to try

}

catch(err) {

  Block of code to handle errors

}

![error](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors-1200x720.jpg)




