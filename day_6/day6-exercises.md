## Day 6 Exercises

If we have a function defined as function sayHello(){console.log("Hello!")}, what is the difference between entering sayHello and sayHello() in the console?
* `sayHello` is interpreted as a variable called sayHello whereas `sayHello()` calls the function named sayHello

What is the difference between function parameters and arguments?
* Parameters are what the function allows you or requires you to enter. Arguments are the actual values passed in as parameters.

What is the keyword return used for?
* Return provides a value to the function callback. It also ends the function.

How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?
* Local variables are better because when the block is over the variable is forgotten saving memory and variable confusion while programming. A scenario you might want to use a globally scoped variable is a counter variable within a function. As a loop runs and adds to the counter each time, you want to return that counter at the end so it would need to be global (or at least scoped outside of the while/for/in loop block).
