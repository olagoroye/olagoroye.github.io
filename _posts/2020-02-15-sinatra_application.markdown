---
layout: post
title:      "JS HOISTING"
date:       2020-02-15 18:44:27 -0500
permalink:  sinatra_application
---

Hoisting is a default JavaScript behavior that determines how variables, functions, and classes are compiled or loaded. Which usually means declaring variables or functions at the top level of a scope.

 
**** Variable Declarations And Hoisting 

 Just before I touch on any of this - let talk about how Variable runs (cycle) . Start from declaration and assignment: when a variable is giving a name  and assigned a value . example is    `var greeting = "hello World!" `,  `var greeting;` will b hoisted to `greeting =  'hello worrld!'`  and  how the variable defined is used .

There are three different  way variables can be defined and identified.  We have `var, let, const`  

** var** , wherever they occur, are processed before any code is executed, this is  the behaviour hoisting exhibit in javaScript, which means declaring a variable anywhere in the code is equivalent to declaring it at the top. try this out in your console                                                     `  console.log(counter) //
                                                                                  var counter = 1  `                                                                                                                            The above will return undefined .       Again let look at this                                                                                                                                                                                                         `var counter;//initialize to undefined  ---
																																									console.log(counter); //undefined--                                
																																									var counter = 1;`    
this is still going to return undefined , because we only hoisted the first line, the we will only get 1 back if we move the console.log after the the var declaration and assigning.  Var is not safe, it  gets hoisted, can be redeclared, can be reassigned.
												 **let**:variables declared with let are also hoisted and lifted to the top although it may not be visible due to that applies to let -which is daclaration and initialization much be expressed before they are accessible.  for example => 'console,log(counter); let counter;' this will throw a reference error. What this means is that if we console.log a let variable ,before it's declared in our code block lt will throw an reference error “cannot be accessed before initialization”.  This error is differnt from the var error of undefined , it actually mean that the compiler recognises the variables exist because it hoisted and but if the code is flipped, the error will be gone but it returns undefined and that's the default intialization when there is no value assignment at variable declaration. It is a good practice to declare our let variable at the top level of our file.                                                                                                                                                                                            **const** variables must be declared and initialized at once in the same statement. However if variable is defined with const when hoisted , they are not initialized with a value of undefined but rather throws the same as the let called Temporal Dead Zone.

												
