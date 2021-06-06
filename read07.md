Control flow


The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. 


A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

For example, the above excerpt might be inside a function that runs when the user clicks the Submit button for the form. The function could also include a loop, which iterates through all of the fields in the form, checking each one in turn. Looking back at the code in the if and else sections, the lines promptUser and submitForm could also be calls to other functions in the script. As you can see, control structures can dictate complex flows of processing even with only a few lines of code.



JavaScript Functions 

JavaScript function is a block of code designed to perform a particular task.A JavaScript function is executed when "something" invokes it (calls it).

JavaScript Function SyntaxA JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

Function InvocationThe code inside the function will execute when "something" invokes (calls) the function:When an event occurs (when a user clicks a button)When it is invoked (called) from JavaScript codeAutomatically (self invoked)Function ReturnWhen JavaScript reaches a return statement, the function will stop executing.If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
The () Operator Invokes the FunctionUsing the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.Accessing a function without () will return the function object instead of the function result.
Functions Used as Variable ValuesFunctions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.
Local VariablesVariables declared within a JavaScript function, become LOCAL to the function.Local variables can only be accessed from within the function.



JavaScript OperatorsThe assignment operator (=) assigns a value to a variable.

```var x = 10;
```
The addition operator (+) adds numbers:
```var x = 5;
```The multiplication operator (*) multiplies numbers.
```var x = 5;
```Multiplying```var x = 5;
```


JavaScript Operators

JavaScript String Operators
The + operator can also be used to add (concatenate) strings.
```
var txt1 = "John";
```
The += assignment operator can also be used to add (concatenate) strings:
```
var txt1 = "What a very ";
```


Adding Strings and Numbers

Adding two numbers, will return the sum, but adding a number and a string will return a string:
```
var x = 5 + 5;
```

