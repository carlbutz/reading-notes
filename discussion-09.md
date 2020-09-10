# Comparison Operators

When comparing two objects with each other, there are number of ways to do this. Each will result in either a true or a false value. That is the comparison is true. Or, the comparison is false. Here are some commong _comparison operators_:

* == **is equal to** - this will compare two values and see if they match, it does not matter if you are comparing different data types. (2 == '2' is true, 2 == 3 is false)
* === **strictly equal to** - this will compare two values and see if they match, this time data types do matter. (2 === '2' is false, 2 === 2 is true)
* != **not equal to** - this will compare two values and see if they are _NOT_ equal, it does not matter if you are comparing to different data types. (2 != '2' is false, 2 != 3 is true)
* !== **strictly not equal to** - this will compare two values and see if they are _NOT_ equal, it does matter if you are comparing to different data types. (2 != '2' is true, 2 != 2 is false)
* > **greater than** - compares two numbers and looks to see if the first number is greater then the second number. (4 > 3 is true, 3 > 4 is false)
* < ** less than** - compares two numbers and looks to see if the first number is less then the second number. (4 < 3 is false, 3 < 4 is true)
* >= **greater than or equal to** - compares two numbers and looks to see if the first number is greater then or equal to the second number. (4 >= 4 is true, 4 >= 3 is true, 3 >= 4 is false)
* <= **less than or equal to** - compares two numbers and looks to see if the first number is less then or equal to the second number. (4 <= 4 is true, 4 <= 3 is false, 3 <= 4 is true)

# Logical Operators

If you need to compare more than two objects, you need to compare two at a time and use a _logical operator_. There are three basic _logical operators_:
* && **Logical AND** - this will only give a true result if both comparisons are true. ((2 < 5) && (3 >= 2)) returns true, ((2 < 5) && (3 <= 2)) returns false
* || **Logical OR** - this will give a true result if both comparisons are true. ((2 < 5) || (3 >= 2)) returns true, ((2 < 5) || (3 <=2)) returns true, ((5 < 2) || (3 <= 2)) returns false
* ! **Logical NOT** - this returns the oposite of what the comparison is. !(2 < 5) returns false, !(3 <= 2) returns true

# Loops

If we need to do a series of steps for a given number of times (counting from 1 to 10) we can use either a for loop or a while loop (there is a do while loop as well, but outside the scope of this class). A _for_ loop is used if you know the number of times something needs to be run. A _while_ loop is better used if you do not know the number of times something needs to be run.

Syntax for a _for loop_
for(var i=0; i<=10; i++) or for(var i=0; i<=100; i=i +10)
In both of these example the var i=0 sets the counter variable up, and sets the starting number. Often the starting number is 0, but it can be any number.
The i<=10 is setting the condition to be met to stop the loop. This condition can be having numbers count up or down. Either way, you just have to set your variabl to increase or decrease accordingly.
It i++ is counting up by 1. the i=i+10 is adding 10 to i each time the loop is run.

Syntax for a _while loop_
var i = 0; [sets the variable up]

while(i <=10){ [sets the limit]

i = i +1 ; [increments to get to the limit]

}

[Return to README.md](/README.md)

