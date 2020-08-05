#Learning to program: Chapter 2

Jeremy Retamar Arrieta
Aug 4 · 5 min read

Last chapter we talked about finding your motivations for wanting to become a software developer or programmer. We covered how to set goals and hold yourself accountable to said goals. Then I shared resources with you to let you know some of what I found really beneficial in my time researching programming. Next we will cover Data types. I will mostly be sticking to Javascript and React for this course. Javascript is the programming language I learned well. React is the framework I worked with for a while.

Data Types:

There are some basic data types every programmer must know. Whether you seek to build micro-service architecture or just building web-apps you will get familiar with these real quick. You will need to learn these basic building blocks of code by heart. In JavaScript the types are loose and dynamic.

It also helps with any Technical interviews you may have in the future. See computers think in 1s and 0s. The way we as humans think is more syntactically. This is why computer programming languages were born. Instead of a long list of numbers we could represent common data structures used to preform a task by assigning it a data type value.

For extended reading on data types please check out the mozilla web development page below:
JavaScript data types and data structures
Programming languages all have built-in data structures, but these often differ from one language to another. This…
developer.mozilla.org

I found mozilla tends to be better at explaining things and w3schools tends to be better at showing you the things that are explained.
Image for post
Image for post
image credit simplesnippets.tech

Additional Resource:

https://simplesnippets.tech/javascript-variables-data-types/

Variables:

When you start programming you are going to be using variables a lot. Variables are items you can assign a value to. Like in algebra x can mean anything. In programming we assign a value to a variable in different ways. You can assign variables to have a value of numbers, strings, a boolean, an array, a function or even an object. Think of it as named storage space. Here is a simple code example using a string:

const pancakes = "flour, eggs, sugar, baking soda"
console.log(pancakes)//The double slashes are for single-line commenting in JavaScipt
//creates variable pancakes assigns it to the string

One of the first data types I learned early on was the good old Boolean. Some people like to start else were like strings and numbers.

Paraphrase or restructure:

In computer science, a boolean data type is any data type that has either a true or false value, yes or no value, or on or off (1 or 0) value. By default, the boolean data type is set to false.

Examples of Booleans in daily life:

    Lights: On or Off
    Time: AM or PM
    Weather: Raining or Not Raining
    Math: Equal to or Not Equal to
    Game: Truth or Dare
    Soda: Coke or Pepsi

I just want to introduce booleans first because you can make a lot of handy arguments with them. Now a boolean is a data type in computer science that is either True or False. See in programming a boolean can be used with conditional statements.

Lets take the statement “If Danny buys oranges then have an advertisement for orange juice pop up.” Now the qualifying statement is “If Danny buys oranges” is True then the advertisement for orange juice should pop up. The statement “If Danny doesn’t buy oranges then pop up general advertisement.” Would only run in the program if Danny doesn’t buy oranges. So in summary this code would run if Danny buys oranges. (example of code inserted here) We will review these booleans later and get into conditional statements further in this course.

Strings:

Strings are great for representing data as text. They are a collection of characters. String primitives and string objects are more advanced.

“ Note that JavaScript distinguishes between String objects and primitive string values. String literals (denoted by double or single quotes) and strings returned from String calls in a non-constructor context (that is, called without using the new keyword) are primitive strings. JavaScript automatically converts primitives to String objects, so that it's possible to use String object methods for primitive strings. In contexts where a method is to be invoked on a primitive string or a property lookup occurs, JavaScript will automatically wrap the string primitive and call the method or perform the property lookup.”

let s_prim = 'foo'
let s_obj = new String(s_prim)

console.log(typeof s_prim) // Logs "string"
console.log(typeof s_obj)  // Logs "object"

credit -developer.mozilla.org

Now decoding the super technical speak above is hard for anyone. The take aways I gathered from them is that JavaScript treats these primitives and objects a little differently than other programming languages do. Most of the time you will not need to worry about the differences between string primitives and string objects unless you have someone giving you a really intense code interview specifically on Javascript. Strings in Python are arrays of bytes representing unicode characters.

“String primitives and String objects also give different results when using eval(). Primitives passed to eval are treated as source code; String objects are treated as all other objects are, by returning the object. ” Example:

let s1 = '2 + 2'              // creates a string primitive
let s2 = new String('2 + 2')  // creates a String object
console.log(eval(s1))         // returns the number 4
console.log(eval(s2))         // returns the string "2 + 2"

credit -developer.mozilla.org

Numbers:

I encourage you to look up and read further into everything when you are studying programming. I understand it is a tedious task. But your future self will thank you for taking the time to read over documentation. If you add two numbers, the result will be a number. When you add a number and a string together the results will be a concatenated string. In JavaScript numbers are always 64 bit floating-points with integers being accurate up to 15 digits. Example:
Tryit Editor v3.6
If you click the save button, your code will be saved, and you get an URL you can share with others.
www.w3schools.com
