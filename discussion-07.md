# Pages 43-69 in JavaScrip & SQuery by Duckett

This section starts to talk about what **JavaScript** (JS) is. It started with a _Do Along_ exercise ([can be found here](https://carlbutz.github.io/jscript-and-jquery-book/c01/add-content.html)). The book then moves on to describe elements found in JS.
* **Object** - a keyword that tells the browser what is being processed in this line
* **Method** - what the Object is going to be doing.
* **Member Operator** - a period that seperates the Object from the Method
* **Parameters** - are the items the method needs to process for the object

An example of this would be: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;member operator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;parameters<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;v&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;v<br>
document&nbsp;&nbsp;&nbsp;.&nbsp;&nbsp;&nbsp;write&nbsp;&nbsp;&nbsp;('Good Afternoon!')<br>
&nbsp;&nbsp;&nbsp;&nbsp;^&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;^<br>
&nbsp;_object_&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;method

This code is all entered into a file with a js extension. Then, the HTML file will call it with a < script > </ script > tag. It is important to remember, where this tag is placed in the HTML file, is where it will be displayed or run in the HTML file.

The book then explains what the different lines of code are called:
* **Statements** - the individual lines of instructions for the computer to follow. Each statement must end with a semi-colon (;)
* **comments** - these are lines, or blocks of lines, the computer will ignore and not run.
   * // - shows a single line comment
   * /*  */ - shows a block comment
* **variables** - a named object the temporarily holds a value. These are case sensative. 
   * Even though _Name_ and _name_ are different, it is considered bad practice to use both in the same bit of JS
   * **Data Types** - 
      * Numeric - a positve or negative number
      * String - letters or words. These must be surrounded by quotes. Either single or double will work, but do not mix them when assigning a variable
      * boolean - a true or false value
   * Variable names must start with a &, _ or a letter. They cannot start with a number
   
To declare a variable, use the _var_ keyword. For example: var price;

To set or change a variable use the name of the variable, the equal sign and then the value

Examples:
var aNumber;
var aString;
var aBoolean;

aNumber = 5;
aString = "Hello World"
aBoolean = true;

If you need a quote inside a string, it is best to use the other type of quote mark that was not used to set the varaible. An example would be:
aString = "this is a quote 'Hello World'";

There are some shortcut ways to declare and set the value of variables, but using these can make reading quote difficult.

[Back to README.md](README.md)
