# Problem Domai

A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics of an individual's interest, and excluding everything else. For example, when developing a system to measure good practice in medicine, carpet drawings at hospitals would not be included in the problem domain. In this example, the domain refers to relevant topics solely within the delimited area of interest: medicine. This points to a limitation of an overly specific, or overly bounded, problem domain. An individual may think they are interested in medicine and not interior design, but a better solution exists outside of the problem domain as it was initially conceived. For example, when IDEO researchers noticed that patients in hospitals spent a huge amount of time staring at acoustic ceiling tiles, which "became a symbol of the overall ambiance: a mix of boredom and anxiety from feeling lost, uninformed, and out of control."


![domin](https://res.infoq.com/articles/ddd-contextmapping/en/resources/ddd-contextmapping-figure1.gif)




# Object Literal
In plain English, an object literal is a comma-separated list of name-value pairs inside of curly braces.
Those values can be properties and functions. Here’s a snippet of an object literal with one property and one function.

JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects. This chapter describes how to use objects, properties, functions, and methods, and how to create your own objects.


    var greeting = {

    fullname: "Michael Jackson",
    greet: (message, name) => {
        console.log(message + " " + name + "!!");
    }
    };

**Objects and properties**

A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

objectName.propertyName

Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive. You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year as follows:

var myCar = new Object();

myCar.make = 'Ford';

myCar.model = 'Mustang';

myCar.year = 1969;



**Object Methods**

Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.


| Property      |     Property Value             |
| -----------  | -----------           |
|    firstName  |  John |
|    lastName  |  Doe |
|    age  |  50 |
|    eyeColor  |  blue |
|    fullName  |  function() {return this.firstName + " " + this.lastName;} |

# DOM
The Document Object Model (DOM) specifies 
how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window. 

![dom](https://www.w3schools.com/js/pic_htmltree.gif)


The W3C DOM standard is separated into 3 different parts:

* Core DOM - standard model for all document types
* XML DOM - standard model for XML documents
* HTML DOM - standard model for HTML documents