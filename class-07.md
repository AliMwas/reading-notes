# Object-Oriented Programming, HTML Tables

**Define an HTML Table**

The < table> tag defines an HTML table.

Each table row is defined with a < tr> tag. Each table header is defined with a < th> tag. Each table data/cell is defined with a < td> tag.

By default, the text in < th> elements are bold and centered.

By default, the text in < td> elements are regular and left-aligned.

## Basic Table Structure

< table>
The < table> element is used 
to create a table. The contents of the table are written out row by row.

< tr>

You indicate the start of each row using the opening < tr> tag.  (The tr stands for table row.) It is followed by one or more < td> 
elements (one for each cell in that row). At the end of the row, you use a closing < /tr> tag.

< td>

Each cell of a table is represented using a < td> element. (The td stands for table data.) At the end of each cell, you use a  closing < /td> tag.


**HTML Table - Add a Border**

To add a border to a table, use the CSS border property:

Example

table, th, td {

  border: 10px solid black;

}

**HTML Table - Add Cell Padding**

Cell padding specifies the space between the cell content and its borders.

If you do not specify a padding, the table cells will be displayed without padding.

To set the padding, use the CSS padding property:

Example

th, td {

  padding: 15px;

}
![table tags](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqjsSx0M7JXTVf-K-YKloLNQfie8c_mN3bhw&usqp=CAU)


## JavaScript Object Constructors

Object Types (Blueprints) (Classes)
The examples from the previous chapters are limited. They only create single objects.

Sometimes we need a "blueprint" for creating many objects of the same "type".

The way to create an "object type", is to use an object constructor function.

In the example above, function Person() is an object constructor function.

Objects of the same type are created by calling the constructor function with the new keyword:

const myFather = new Person("John", "Doe", 50, "blue");
const myMother = new Person("Sally", "Rally", 48, "green");

The this Keyword
In JavaScript, the thing called this is the object that "owns" the code.

The value of this, when used in an object, is the object itself.

In a constructor function this does not have a value. It is a substitute for the new object. The value of this will become the new object when a new object is created.

Adding a Property to a Constructor
You cannot add a new property to an object constructor the same way you add a new property to an existing object:

Example
Person.nationality = "English";

Built-in JavaScript Constructors
JavaScript has built-in constructors for native objects:

* new String()    // A new String object

* new Number()    // A new Number object

* new Boolean()   // A new Boolean object

* new Object()    // A new Object object

* new Array()     // A new Array object

* new RegExp()    // A new RegExp object

* new Function()  // A new Function object

* new Date()      // A new Date object