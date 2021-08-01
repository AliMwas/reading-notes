# Summarize Expressions, operators and Loops in JS

JavaScript has many types of operators and this is a list of some of them:

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators

1. Assignment operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, A = B assigns the value of A to B.

2. Comparison operators

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. 

3. Arithmetic operators

An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).

The iteration in programming is very useful so allows us to simplify our algorithm by stating that we will repeat certain steps until told otherwise. This makes designing algorithms quicker and simpler because they don't have to include lots of unnecessary steps, in addition, to make the code cleaner and organized.

One of the most common loops is the "for" in addition to "while"

**For statement**

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java for a loop.

A for statement looks as follows:
for(initial; condition; increment or decrement){


here is the code you need to repeat it

}
while statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition){
  
 here is the code you need to repeat it
 
 }