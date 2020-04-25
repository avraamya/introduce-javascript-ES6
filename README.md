# introduce-javascript-ES6
Small project - which introduces the new changes to JavaScript

In the project I am presenting some changes for Java script.
Changes that appeared in the sixth version of the language.

The project describes the following:

"Suppose that you're working in a small town administration, and you're in charge of two town elements:
1. Parks
2. Streets
It's a very small town, so right now there are only 3 parks and 4 streets. All parks and streets have a name and a build year.
At an end-of-year meeting, your boss wants a final report with the following:
1. Tree density of each park in the town (forumla: number of trees/park area)
2. Average age of each town's park (forumla: sum of all ages/number of parks)
3. The name of the park that has more than 1000 trees
4. Total and average length of the town's streets
5. Size classification of all streets: tiny/small/normal/big/huge. If the size is unknown, the default is normal
All the report data should be printed to the console.
HINT: Use some of the ES6 features: classes, subclasses, template strings, default parameters, maps, arrow functions, destructuring, etc.
"

The project is not complicated. Building an element class. 2 classes, "Street" and "Park" inherit it and add their features.

One of the innovations in this version is the use of "template string". You can see how we used it in the project. 

At some point in the object we had to use the object called - Map. The "street" object has a feature that classifies the street by size.
Each size has a different classification. So what can be done is by the size of the street - find the appropriate organ on the map.

We were asked to classify as "normal" by default. So we can say that the size that describes the "normal" - it will be by default.

Because we have 4 "Park" objects - put them all together - for convenience.

We built 2 functions - which describe the occurrence of events for both object types.

In the object set we will need to make "loops" - because these are arrays - it is more convenient to use "foreach" loops.

Something very important - an arrow function - can only be used when we call a function - when a function already exists.

A function (non-anonymous function) cannot be exercised with an arrow. Arrow function does not take up space - so this software will not work properly. The "this" attribute will point to the window object, and not to the object we want. It is also important to note where the scoop of an arrow function is called.

In a normal function, another function can be used - the arrow function. And because the arrow function has no space - it will take this from the function it called.

The calc function - performs two identical calculations - that uses the same data. Therefore two things can be calculated and returned in one set. And then use the destruction principle.

We have a passage of objects - and we need a certain feature of each object. Map function can be used. It will go over the array of objects and return an array with the desired attribute of each object.

We can do the same thing for Task 3. We will return an array by map. And on this array we will turn on the "indexOf".
