      JavaScript (JS)

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming .language with first-class function.
JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript.

This section is dedicated to the JavaScript language itself, and not the parts that are specific to Web pages or other host environments.

Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantic, and use.

IntermediateUnderstanding client-side JavaScript frameworksJavaScript frameworks are an essential part of modern front-end web development, providing developers with proven tools for building scalable, interactive web applications. This module gives you some fundamental background knowledge about how client-side frameworks work and how they fit into your toolset, before moving on to tutorial series covering some of today's most popular ones.In the JavaScript code we have a function called say_hi. It used the getElementById we have already seen to locate the DOM element representing the input element with the id first_name. The object returned has a method value that will return the text the user has typed in that field.We use this technique to retrieve the content of both input fields and assign their content to two variables: fname and lname.Then, using these variable we create an HTML snippet and assign it to a new variable called html.


** JavaScript Identifiers All JavaScript variables must be identified with unique names.These unique names are called identifiers.Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).The general rules for constructing names for variables (unique identifiers) are:Names can contain letters, digits, underscores, and dollar signs.Names must begin with a letterNames can also begin with $ and _ (but we will not use it in this tutorial)Names are case sensitive (y and Y are different variables)Reserved words (like JavaScript keywords) cannot be used as namesThe Assignment OperatorIn JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.This is different from algebra. The following does not make sense in algebra:x = x + 5

1. JavaScript Data Types:
```
var pi = 3.14;
```
2.Value = undefined:
 ```
 var carName;

 3.Re-Declaring JavaScript Variables:
 ```
 var carName;
```
 4.JavaScript Arithmetic :
 ```
 var x = 5 + 2 + 3;
```
 5.JavaScript Dollar Sign $ :
 ```
 var $ = 2;
 ```