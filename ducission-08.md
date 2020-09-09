# Pages 1-24

JavaScript allows a programmer, and ultimately the end user, the ability to 
1. **access** content on a web page
2. **modify** the content on a web page
3. **program** what the page is going to do
4. **react** to events that take place on the web page

We can think of a script as either a recipe, handbook or manual. These all tell a person how to do something, and that is what a script is, it tells the computer what to do. Unlike a human, a script is needed everytime the computer needs to do something, even if it has done it before. Typically, when a human learns to do something, they can do it over and over again, without activly thinking about it. A computer cannot do this, it does not learn.

When writing a script, we need to know the vocabulary, or _keywords_, the computer will need to do what it is we want it to do. We also need to know the _syntax_, or how we put the keywords together.

On pages 18 and 19 are good examples of how a flowchart (visual representation of a program, with all logic thought out) can be converted into the steps of a program.

The other good example, that show the difference between a human and a computer, is found on pages 20 and 21. It shows pictures of people and asks to rank in height order from tallest to shortest. As a human, we would just look at the group and move them around. In order for the computer to do this, it has to repeatedly check one person against the next, and move as needed. If it finds that one person is taller that the previous, it will move to the new order, and start the process again until all people are in the correct order.

# Pages 74 - 79

**Expressions** evaluates something and returns one value. There are two types of basic expressions
1. _Assiging_ a value into a variable. So var color = 'beige'; is an expression that assigns beige to the variable color
2. _Evaluating_ two or more values into a single variable or result. So, var ans = 2 + 3; would assign 5 to the vasiable 5

There are a number of operators that can be used in JavaScript
* **Assignment** - that setting one value equal to another (color = 'beige')
* **Arithmetic** - doing math with two or more numbers (area = 3 * 2)
* **String** - manipulating two or more strings (name = 'Carl ' + 'Butz')
* **Comparision** - checking to see if the statment is true or not (buy = 3 > 5)
* **Logicial** - checking two or more comparisions, depending on if it is an AND or an OR will give a different result for the question (buy = (5 > 3) && (2 < 4))

There are a number of _arithmetic operators_:

Name | Operator | Purpose & Notes | Examples | Result
--- | --- | --- | --- | ---
Addition | + | adds numbers together | 2 + 3 | 5
Subtraction | - | subtracts one number from another | 3 - 2 | 1
Division | / | divides one number with another | 6 / 2 | 3
Multiplication | * | multiples one number and another | 2 * 3  | 6
Increment | ++ | adds 1 to the current number | i = 10; i++; | 11
Decrement | -- |subtracts 1 from the current number | i = 10' i-- | 9
Modulus | % | divides two numbers and gives the remainder | 9 % 4 | 1

Just like the math we learned in middle school, the order of operation is followed: PEMDAS (Parentheses, Exponents, Multiplication/Division, Addition/Subtraction). So 2 + 3 * 5 is different the (2 + 3) * 5. The first will result in 17 (3 * 5 = 15 + 2 = 17). The second will result in 25 (2 + 3 = 5 * 5 = 25).

The only operator that can be used with string values is the +, it is used to concatenate (join) two strings together. This will do it literally, so '7' + '9' = '79'

# Pages 88 - 94

This section talks about functions. Functions are useful when a series of steps need to happen over and over again in a script. Rather than re-writing the code each time it is needed, you can write a function one time, and have it called multiple times.

To **delcare** a function you use the keyword function, then give a name, list any parameters needed, and then what that function should do:
function hw(){document.write('Hello World!');}

To **call** a function you list its name and any needed parameters where you want it to happen in the script:
hw();

You can get single or multiple values out of a function. To return a single value:
return area; (assuming area was defined in the function proior to this line)

To return multiple values:
sizes = [area, volume] (assuming area and volume were defined earlier in the function)

When working with one result:
var res = functionName(3, 5);

When working with multiple results:
var res = functionName(3, 2, 3)[0] (returns the first result in return value)

[Return to README.md](/README.md)
