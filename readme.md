# 100 Days Of Code - Log
Welcome to my journal for the 100DaysOfCode challenge. If you'd like to learn, connect, and grow with me, follow me on [Twitter](https://twitter.com/wordsbyfifi/), [Medium](https://anthonynanfito.medium.com/), or check out [my porfolio](https://ananfito.github.io/). Thanks for stopping by. Happy Coding!

### Day 32: September 06, 2022

**Today's Progress:** I continued working on the Tetris game, based on the [tutorial by Ania Kubow](https://github.com/kubowania/Tetris-Basic). I attempted to replace the `keyCode` with `key` in the `control()` function (since `keyCode` is deprecated) using the `switch` method (instead of an `if` statement), but then the `control()` function stopped working. I'll need follow-up on that.

I also (re)attempted to find the error in the section for the up-next Tetromino from yesterday. Specifically, it won't display the up-next Tetromino in the mini-grid on the rightside of the page. I re-watched that [segment](https://youtu.be/rAUn1Lom6dw?t=3938) of the tutorial and compared my code with [hers](https://github.com/kubowania/Tetris-Basic/blob/master/app.js) (line-by-line). Still not sure what's wrong with it. Now I'm waiting for feedback from others.

**Thoughts:** I feel like I'm teetering between frustration and insanity. Okay, that's probably an over exaggeration. Those things are indeed true, but in a good way I think. Obviously trying to figure out what's wrong with code that doesn't run correctly is all part of the job, but I know eventually there will be some solution found. And my job is to keep searching and enjoy the search (like a quest). At least, that's the mindset I'm adopting.

In other words, I am frustrated but in a good way. I'm enjoying the process of trying to figure out why it doesn't work because it's forcing me to learn more deeply about various JS methods, access resources (like documentation and asking for help on forums), and (perhaps most importantly) keep going. It's easy to want to give up and stop, but I know that nothing worth having is given without effort.

**Link to work:** https://github.com/ananfito/basic-tetris

### Day 31: September 05, 2022

**Today's Progress:** I continued working on the Tetris game, based on the [tutorial by Ania Kubow](https://github.com/kubowania/Tetris-Basic). Today I updated the `freeze()` function, added/reorganized the `div` on the HTML page to move the display box, and I created the `displayShape()` function.

**Thoughts:** Overall, I'm able to follow along with this tutorial and it's nice to see how things work in a practical setting, BUT for some reason my code doesn't do what hers does in the video. I suspect there's some sort of formatting error in mine, but I can't find it (or perhaps a typo).

Yesterday, I had a similar issue and asking for help solved the issue (it was great to have another set of eyes look things over). I plan to do the same for the issue I'm having now. I have to admit it's a little frustrating because I've checked (and rechecked) my code and as far as I can see it matches her instructions as well as what she has in the repo. But this is why we have forums, study buddies, Discord servers, and colleagues to poke when we're stuck.

**Link to work:** https://github.com/ananfito/basic-tetris

### Day 30: September 04, 2022

**Today's Progress:** Today I continued working building a basic Tetris game using JavaScript. I've been following the tutorial ["Code Tetris: JavaScript Tutorial for Beginners"](https://youtu.be/rAUn1Lom6dw) taught by Ania Kubow. Today I added functions for `freeze`, `moveLeft`, and `moveRight`.

**Thoughts:** I'm really enjoying this project because it's showing me how various JS concepts were in action. A lot of the challenges on fCC and in other places are often done in isolation so it's difficult for a beginner to understand how they work.

Also, I've noticed that a lot of examples will use a mathematical example (like creating a loop that adds 1 each time) but don't always use a more practical example. Don't get me wrong, as a mathematics teacher I enjoy seeing how the math works out, but more often than not a lot of these concepts will be used to create muliple `div` boxes for your grid in Tetris (just as a more concrete example).

Overall, I'm happy with the progress I made. And I'm happy I decide to look for extra resources to learn these concepts. When I got frustrated yesterday there was a small part of me that wanted to give up, but I'm grateful I persevered. I'm also glad I reached out for help on the freeCodeCamp Discord server when I got stuck.

**Link to work:** https://github.com/ananfito/basic-tetris

### Day 29: September 03, 2022

**Today's Progress:** Today I continued completing challenges on the [Functional Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#functional-programming) section freeCodeCamp's JavaScript course (33% complete so far) and I read Chapter 7 'Project: A Robot' from [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marijn Haverbeke. The challenges on fCC focused on functional programming and the chapter from *Eloquent JavaScript* featured a description of a project.

*Quotes & Key Ideas:*

Notes from freeCodeCamp:
- "*Callbacks* are the functions that are slipped or passed into another function to decide the invocation of that function. You may have seen them passed to other methods, for example in filter, the callback function tells JavaScript the criteria for how to `filter` an array."
- "Functions that can be assigned to a variable, passed into another function, or returned from another function just like any other normal value, are called *first class* functions. In JavaScript, all functions are first class functions."
- "The functions that take a function as an argument, or return a function as a return value, are called *higher order* functions."
- "When functions are passed in to or returned from another function, then those functions which were passed in or returned can be called a *lambda*."
- "One of the core principles of functional programming is to not change things. Changes lead to bugs. It's easier to prevent bugs knowing that your functions don't change anything, including the function arguments or any global variable."
- "in functional programming, changing or altering things is called *mutation*, and the outcome is called a *side effect*. A function, ideally, should be a *pure function*, meaning that it does not cause any side effects."
- "Another principle of functional programming is to always declare your dependencies explicitly. This means if a function depends on a variable or object being present, then pass that variable or object directly into the function as an argument."
- "The `map` method iterates over each item in an array and returns a new array containing the results of calling the callback function on each element. It does this without mutating the original array."
- "`filter` calls a function on each element of an array and returns a new array containing only the elements for which that function returns `true`."

Notes from *Eloquent JavaScript*:
- "The fact that something sounds like an object does not automatically mean that it should be an object in your program. Reflexively writing classes for every concept in your application tends to leave you with a collection of interconnected objects that each have their own internal, changing state. Such programs are often hard to understand and thus easy to break"
- "Data structures that don’t change are called *immutable* or *persistent*"

**Thoughts:** Today I'm feeling a little frustrated. I'm not sure if it's because I'm tired or if I'm not fully understanding the concepts of JavaScript. While reading *Eloquent JavaScript* I felt completely lost the entire time (and will probably need to re-read the chapter).

Later, while working on the challenges on fCC I had to look up countless tutorials, read (and re-read) the hints, and look up the solutions. And I still felt lost. Some solutions were so simple I didn't understand why they were a "challenge" at all, and others felt like they weren't placed appropriately - like the needed more explaining and scaffolding or should have been broken up into smaller steps.

Overall, I'm glad I put some study time in, but I think I need to walk away from the keyboard and try again tomorrow.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

#### ADDENDUM:
**Progress Update:** After taking a break, my frustration dissapated and I got bored. So looked up some JavaScript tutorials on YouTube. I saved some for future reference, but settled on the [Code Tetris: JavaScript Tutorial for Beginners](https://youtu.be/rAUn1Lom6dw) on the freeCodeCamp YouTube Channel taught by [Ania Kubow](https://www.youtube.com/channel/UC5DNytAJ6_FISueUfzZCVsw).

**Thoughts:** I think this is something that I needed. My earlier frustration was due both to fatigue as well as having things explained in isolation. This Tetris tutorial helped me see certain JavaScript features and concepts in action. Also, I like how at certain points Ania explains what the concept is by giving a definition and then demostrates how it'll be used in the app.

I'm not yet finished with the app (I left off at 45m30s), but you can view my progress in the link below. I am excited about this tutorial project because Tetris is one of my favorite games to play. Watching the tutorial based on something I'm already familair with is helping me line of sets of knowledge in my brain and making the learning more fun.

**Link to work:** https://github.com/ananfito/basic-tetris

### Day 28: September 02, 2022

Rest day.

### Day 27: September 01, 2022

**Today's Progress:** Today I started the [Functional Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#functional-programming) section freeCodeCamp's JavaScript course. I've completed 4% so far.

*Quotes & Key Ideas:*
- "Functional programming is a style of programming where solutions are simple, isolated functions, without any side effects outside of the function scope: `INPUT -> PROCESS -> OUTPUT`"

**Thoughts:** Today's session was short. I only got through one challenge because I had a headache which later developed into a migraine attack so I never went back later in the day to continue studying.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 26: August 31, 2022

**Today's Progress:** Today I finished the [Object Oriented Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#object-oriented-programming) section of the JavaScript course from freeCodeCamp. Today's challenges focused on how `constructors`, `prototypes`, *subtypes*, *supertypes*, *inheritance*, and *mixins*.

*Quotes & Key Ideas:*
- When using a *constructor* the `new` operator is needed when calling the constructor such as in the example below. This will create a new object, `blueBird` with the properties `blueBird.name`, etc. It can then be accessed and modified just like any other property within an object.  
```
function Bird() {
  this.name = "Albert";
  this.color  = "blue";
  this.numLegs = 2;
}

let blueBird = new Bird();
```
- To make *constructors* more flexible we can design them to accept variables as parameters so that it's easy to construct the objects with the appropriate/desired properties. For example:
```
function Bird(name, color) {
  this.name = name;
  this.color = color;
  this.numLegs = 2;
}

let cardinal = new Bird("Bruce", "red");
```
- "Anytime a constructor function creates a new object, that object is said to be an *instance* of its constructor. JavaScript gives a convenient way to verify this with the `instanceof` operator. `instanceof` allows you to compare an object to a constructor, returning `true` or `false` based on whether or not that object was created with the constructor."
- "Properties in the `prototype` are shared among ALL instances of" the constructor object and "Since all instances automatically have the properties on the `prototype`, think of a `prototype` as a "recipe" for creating objects." For example, `Bird.prototype.numLegs = 2;` will give the property `numLegs` the value of `2` for all objects created using the `Bird` constructor.
- "*Own properties* are defined directly on the object instance itself. And prototype properties are defined on the `prototype`." For example:
```
function Bird(name) {
  this.name = name;  //own property
}

Bird.prototype.numLegs = 2; // prototype property

let duck = new Bird("Donald");
```
- "There is one crucial side effect of manually setting the prototype to a new object. It erases the `constructor` property! ... To fix this, whenever a prototype is manually set to a new object, remember to define the `constructor` property:
```
Bird.prototype = {
  constructor: Bird,
  numLegs: 2,
  eat: function() {
    console.log("nom nom nom");
  },
  describe: function() {
    console.log("My name is " + this.name);
  }
};
```
- "Just like people inherit genes from their parents, an object inherits its `prototype` directly from the constructor function that created it."
- The `isPrototypeOf` method will show the relationship of the object and the constructor that created it
- "All objects in JavaScript (with a few exceptions) have a `prototype`. Also, an object’s `prototype` itself is an object"
- The principle of *Don't Repeat Yourself* (DRY) is used in programming because repetitive programs become harder to modify when changes are needed. This leads to more work, which can also lead to more errors. We can use inheritance to help reduce repetition in programs.
- "`Object.create(obj)` creates a new object, and sets `obj` as the new object's `prototype`". For example, `let duck = Object.create(Animal.prototype);` will create `duck` as an *object* with the prototype based on the `Animal` constructor.
- `Bird.prototype = Object.create(Animal.prototype);
` will create a *subtype* based on the *supertype* `Animal` in which `Bird` will have all of the properties defined by the `Animal` constructor.
- "When an object inherits its `prototype` from another object, it also inherits the supertype's constructor property."
- "A constructor function that inherits its `prototype` object from a supertype constructor function can still have its own methods in addition to inherited methods."
- Inheritance works great for objects that are related, but not-so-great for objects that are not related. "For unrelated objects, it's better to use *mixins*. A mixin allows other objects to use a collection of functions." For example, both a `Bird` and an `Airplane` can fly, but a `Bird` is not an `Airplane` and vice versa. So we can create the `flyMixin` to take any object and give it the `fly` method:
```
let flyMixin = function(obj) {
  obj.fly = function() {
    console.log("Flying, wooosh!");
  }
};
```
- "In JavaScript, a function always has access to the context in which it was created. This is called `closure`."
- **Immediately Invoked Function Expression (IIFE):**
"A common pattern in JavaScript is to execute a function as soon as it is declared:
```
(function () {
  console.log("Chirp, chirp!");
})();
```
This is an anonymous function expression that executes right away, and outputs `Chirp, chirp!` immediately.

Note that the function has no name and is not stored in a variable. The two parentheses `()` at the end of the function expression cause it to be immediately executed or invoked. This pattern is known as an *immediately invoked function expression or IIFE*."
- "An immediately invoked function expression (IIFE) is often used to group related functionality into a single object or *module*."

**Thoughts:** Most of the challenges were really easy because they involved copying or rewriting code from the example. Which is okay since the last section (Algorithm Scripting) was rather difficult, but I was hoping for more of challenge than just changing a few words in lines of code. Perhaps that will come in the next section (Functional Programming).

That said, I was delighted to see how `constructors` and `prototypes` work in practice. Previously, when I read about them in *Eloquent JavaScript* I found them a bit confusing on a conceptual level, but I think they're starting to make a bit more sense.

Lastly, I'm feeling especially grateful to my partner who's been very supportive during this programming journey. On this particular evening, he prepared dinner which gave me more time to study. (-:

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 25: August 30, 2022

**Today's Progress:** Today I completed the [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp and started the [Object Oriented Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#object-oriented-programming) section. I'm currently 19% done.

*Quotes & Key Ideas:*
- Similar to real-life objects, *objects* in JavaScript contain properties and values. For example:
```
let dog = {
  name: "Spot",
  numLegs = 4
};
```
- "Objects can have a special type of property, called a method. Methods are properties that are functions. This adds different behavior to an object."
- The `this` keyword is used to refer to the name of the object. For example:
```
let duck = {
  name: "Aflac",
  numLegs: 2,
  sayName: function() {return "The name of this duck is " + this.name + ".";}
};
```
- "*Constructors* are functions that create new objects. They define properties and behaviors that will belong to the new object. Think of them as a blueprint for the creation of new objects."
- "Constructors follow a few conventions:

    - Constructors are defined with a capitalized name to distinguish them from other functions that are not `constructors`.
    - Constructors use the keyword `this` to set properties of the object they will create. Inside the constructor, `this` refers to the new object it will create.
    - Constructors define properties and behaviors instead of returning a value as other functions might."

*References:*

I found the following tutorials/guides useful in today's session:
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice

**Thoughts:** I'm very delighted that I completed the last challenge in the Basic Algorithm Scripting section. Those challenges were difficult, but worth it. It felt good to put into practice what I've been learning so far.

I've only just begun the Object Oriented Programming section, but so far it's going well. I'm especially enjoying seeing how things like *constructors*, and the `this` keyword is put into use. Previously, while reading *Eloquent JavaScript* I struggled to understand these concepts. I won't say I fully understand them now, but I'm getting there.

In addition to programming, I also took some time to connect with others via Discord. This is a part of my programming journey that I think I've neglected and would like to dedicate more time to. Overall, I'm satisfied with today's study session. As with yesterday's session, I stuck with the [Mozart's Piano Concerto No. 23](https://youtu.be/BMYjGkgzinU) on repeat to stay focus.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 24: August 29, 2022

**Today's Progress:** I completed challenges on the [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp. I'm currently 94% complete with this section. The challenges focused on using loops, indexing, string conversion, and other concepts learned up until this point.

**Thoughts:** As with the previous challenges in this section they are both exciting and difficult to complete. I'm enjoying being able to start a script from scratch and work to completion on it, but also finding it difficult when it doesn't work. I'm know this is all part of the learning process and probably mimics what a developer's job is like, but diving in tutorials and forum posts is not as convenient as poking your co-working for help when you need it.

Overall, I'm satisfied with my progress today. I would have liked to finish the section completely (only one challenge left!), but I'm too tired from the work day.

For music today, I drifted away from *Battlestar Galactica* and listened to [Mozart's Piano Concerto No. 23](https://youtu.be/BMYjGkgzinU) on repeat.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

*References*

I found the following tutorials useful in today's session:
- https://forum.freecodecamp.org/t/javascript-string-prototype-indexof-index-of-explained-with-examples/15936
- https://forum.freecodecamp.org/t/how-to-use-javascript-array-prototype-sort-javascript-sort-explained-with-examples/14306
- https://www.freecodecamp.org/news/falsy-values-in-javascript/
- https://www.bitdegree.org/learn/javascript-filter
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
- https://attacomsian.com/blog/javascript-convert-string-to-array
- https://www.geeksforgeeks.org/javascript-sort-method/
- https://www.w3schools.com/jsref/jsref_filter.asp

### Day 23: August 28, 2022

**Today's Progress:** Today I read Chapter 6 'The Secret Life of Objects' in [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marijn Haverbeke and I completed a few challenges on [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp. I'm currently 69% complete with this section.

Here are some quotes and key ideas from *Eloquent JavaScript*:
- "The core idea in object-oriented programming is to divide programs into smaller pieces and make each piece responsible for managing its own state."
- "Different pieces of such a program interact with each other through interfaces, limited sets of functions or bindings that provide useful functionality at a more abstract level, hiding their precise implementation."
- JavaScript currently doesn't support a way to distinguish from public and private properties so "it is also common to put an underscore (`_`) character at the start of property names to indicate that those properties are private."
- *Encapsulation* is the idea of separating interface from implementation
- "In addition to their set of properties, most objects also have a *prototype*. A prototype is another object that is used as a fallback source of properties."
- "JavaScript’s prototype system can be interpreted as a somewhat informal take on an object-oriented concept called *classes*. A class defines the shape of a type of object—what methods and properties it has. Such an object is called an *instance* of the class."
- "By convention, the names of constructors are capitalized so that they can easily be distinguished from other functions."
- "JavaScript classes are constructor functions with a prototype property."
- "The `class` keyword starts a class declaration, which allows us to define a constructor and a set of methods all in a single place."
- In programming, the word *map* refers to two different things: as a *verb* it means to transform a data structure by applying a function to it while as *noun* it is a data structure that associates values (the keys) with other values.
- To avoid confusion, "JavaScript comes with a class called `Map`that is written for this exact purpose. It stores a mapping and allows any type of keys"
- "The methods `set`, `get`, and `has` are part of the interface of the `Map` object"
- "When a piece of code is written to work with objects that have a certain interface—in this case, a `toString` method—any kind of object that happens to support this interface can be plugged into the code, and it will just work. This technique is called *polymorphism*. Polymorphic code can work with values of different shapes, as long as they support the interface it expects."
- "Symbols are values created with the `Symbol` function. Unlike strings, newly created symbols are unique—you cannot create the same symbol twice."

**Thoughts:** The concepts in Chapter 6 of *Eloquent JavaScript* were challenging to wrap my brain around. I think I'll need to read more about how prototypes, classes, symbols, and matrices work in JavaScript. I also found the challenges on freeCodeCamp difficult as well, particularly the challenge about capitalizing the first letter in a string.

My first attempt did not work. I surfed around the internet to find some ideas for solutions, but those didn't work either (see below for some references). In the end, I consulted the [freeCodeCamp hints and solutions](https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-title-case-a-sentence/16088). I modeled my response after that, but I'm still unsure why my first attempt didn't work and (stupidly) I didn't save it so I could play around with it later, outside of freeCodeCamp's interpreter, or show it to someone else to get help on it. -_-

Overall, while today's session was challenging it was a good reminder to be patient and move slowly.

*References I found useful*:
- https://attacomsian.com/blog/string-capitalize-javascript (I didn't save my first attempt, but I modeled after this tutorial - next time, I'll save more work so I can ask for help from others. #liveandlearn)
- https://www.w3schools.com/jsref/jsref_split.asp
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet
- https://www.w3schools.com/jsref/jsref_join.asp

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 22: August 27, 2022

**Today's Progress:** Today I read through Chapter 5 'Higher-Order Functions' of [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marijn Haverbeke. This chapter focused on using *abstraction* to write simpler, easy-to-read programs/scripts. Below are my notes from today's reading.

*Quotes & Key Ideas:*
- "'There are two ways of constructing a software design: One way is to make it so simple that there are obviously no deficiencies, and the other way is to make it so complicated that there are no obvious deficiencies.' - C.A.R. Hoare, 1980 ACM Turing Award Lecture"
- "Functions that operate on other functions, either by taking them as arguments or by returning them, are called *higher-order functions*. ... Higher-order functions allow us to abstract over *actions*, not just values."
- "The `map` method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been *mapped* to a new form by the function."
- "Another common thing to do with arrays is to compute a single value from them." When we compute a single value (like finding the sum, or the element with the most characters) we are “reducing” (or folding) the array.
- "Higher-order functions start to shine when you need to *compose* operations
- It’s not enough to just write eloquent or simple, easy-to-read scripts. It’s also important to be strategic about what those scripts are going to be used for/on. In other words, what are the actual computations the computer will do and how much energy/time will it consume to do so.
- "The `some` method is another higher-order function. It takes a test function and tells you whether that function returns true for any of the elements in the array."
- "If you have a character (which will be a string of one or two code units), you can use `codePointAt(0)` to get its code."

**Thoughts:** It's been a long week. Long story short, I've got a back/neck ache due to a poor ergonomic desk setup at work (still troubleshooting that) and I had some gastro-intestinal issues that required a day of rest. As such, I haven't got a lot of actually coding done lately. The past two days were Rest Days and today I only read through a chapter of *Eloquent JavaScript*.

However, I am enjoying reading through this book. Combined with the exercises I've been doing on freeCodeCamp I'm finding it helpful to reinforce the concepts and see things explained in a different way.

Admittedly, I am bit sad about not getting to work on sitting down at the desk and coding, but my health has to take a priority. I'm still not quite feeling 100%, but hopefully tomorrow I'll be rested and ready to get back at it.

### Day 21: August 26, 2022

Rest day.

### Day 20: August 25, 2022

Rest day.

### Day 19: August 24, 2022

**Today's Progress:** Today I continued working on the [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp. I'm currently 62% complete with this section. Today's challenges focused on writing algorithms to solve a specific task and incorporated a lot of the concepts taught up until this point. I worked on writing scripts for repeating a string, finding an element in an array, and checking the value for Booleans.

**Thoughts:** I ran out steam working on today's session - I didn't get as far as I wanted (it was a long day at work), but I'm grateful I got a few challenges complete. As with my previous days' entries, I'm enjoying how these challenges are setup. It's been good to put into practice what I've learned and it's really, really gratifying when I can write the script and get it to work. I'm hoping to make more progress as the week goes on.

While I studied today I used a pencil and paper to sketch out the pieces of the algorithm before I actually sat down to type it out. This turned out to be a useful strategy. I hadn't realized how difficult it was keeping it all straight in my head. As with other strategies I'm learning on this journey, I'll have to keep that one in my "toolkit" when I'm stuck.

For reference, here are some of the tutorials I found useful during today's challenges:
- https://attacomsian.com/blog/string-capitalize-javascript
- https://www.w3schools.com/jsref/jsref_split.asp
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet (very handy cheatsheet for regex shorthand)
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions
- https://stackoverflow.com/questions/9169764/javascript-regex-shorthand

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 18: August 23, 2022

**Today's Progress:** Today I continued working on the [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp. I'm currently 44% complete with this section. Today's challenges focused on writing algorithms to solve a specific task and incorporated a lot of the concepts taught up until this point.

**Thoughts:** As with yesterday's session, today's challenges were exercise based instead of guided examples. This made it more challenging because you're writing full algorithm scripts instead of just changing a few lines here or there to demonstrate a concept. I enjoyed this challenge because (again) it's an opportunity to put into practice what I've learned up until this point, as well as practicing vital problem-solving skills (i.e., knowing how to find the right resources to solve your problem).

I'm very satisfied with today's session and only sad that I didn't have more time and energy to work though more challenges, but that's okay because rest is also an important component of learning (gotta give those brain neurons time to connect).  

For reference, here are some of the tutorials I found useful:
- https://www.w3schools.com/jsref/jsref_slice_string.asp
- https://www.w3schools.com/js/js_loop_while.asp

Today I decided to switch up my focus music (slightly). Today I chose to listen to [*Fight Night*](https://youtu.be/luEnIGXO1d0) instead of [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) from the Battlestar Galactica soundtrack (which by the way, I just noticed I spelled incorrectly in my previous posts -__-). This song is shorter than, but has a similar pace/beat as *Prelude to War*. I like the use of drums, I feel it keeps me moving forward. Again, I listened to it on repeat with noise-reduction headphones.

I forget where I learned it, but I remember reading how listening to music on repeat helps keep you focused because the brain isn't wasting energy on "deciphering" the patterns in the music. It already knows what's coming so now it can focus on other tasks, like writing algorithm scripts. I learned that a few years ago and it seemed to work for me so now it's my go-to trick for when I need to sit down and focus deeply on something.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 17: August 22, 2022

**Today's Progress:** Today I started the [Basic Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-algorithm-scripting) section of the JavaScript course from freeCodeCamp. I'm currently 31% complete with this section. Today's challenges focused on writing algorithms to solve a specific task and incorporated a lot of the concepts taught up until this point.

**Thoughts:** Today's challenges were more exercise-based rather than guided examples. I really enjoyed this because it was an opportunity to put what I've learned so far into practice. Specifically, I got to practice creating algorithms that used loops to count elements of arrays or write function to accomplish a task like finding the largest word in a string. And I got to practice finding solutions on my own via web/forum searches to piece together the program (a key skill for any developer).

For reference, here are some of the tutorials I found useful:
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length
- https://stackabuse.com/how-to-convert-a-string-to-an-array-in-javascript/
- https://eloquentjavascript.net/03_functions.html
- https://www.w3schools.com/js/js_loop_forin.asp

As usual, to help stay focused I listened to the Battlestar Galactica song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) on repeat via headphones with noise-reduction.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 16: August 21, 2022

**Today's Progress:** Today I completed the second half of the [Basic Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-data-structures) section on  the JavaScript course from freeCodeCamp. Next, I'll be moving on to 'Basic Algorithm Scripting'. Today's challenges focused on interacting with nested arrays and objects. Below are my notes and reflection from today's session.

*Quotes & Key Ideas:*
 - "`indexOf()` takes an element as a parameter, and when called, it returns the position, or index, of that element, or -1 if the element does not exist on the array."
 - "JavaScript offers several built in methods that each iterate over arrays in slightly different ways to achieve different results (such as `every()`, `forEach()`, `map()`, etc.), however the technique which is most flexible and offers us the greatest amount of control is a simple `for` loop."
 - "At their most basic, objects are just collections of *key-value* pairs. In other words, they are pieces of data (*values*) mapped to unique identifiers called properties (*keys*)."
 - You can use the dot notation to add key-value pairs to an object (e.g., `contact.email = 'messagme@mail.com';`). However, if the new property (*key*) has as a space in it, then the bracket (`[]`) notation must be used (e.g., `contact['phone number'] = '1-800-2633';`).
 - To remove a *key* from an object use the keyword `delete`. For example, `delete foods.apples;` will remove the `apples` key from the `foods` object.
 - How to check for a property: "JavaScript provides us with two different ways to do this. One uses the `hasOwnProperty()` method and the other uses the `in` keyword." For example, let's say we have an object called `users` and within there is a property (*value*) called `'Alan'`, then `users.hasOwnProperty('Alan');` and `'Alan' in users;` will both return `true`.
 - "Sometimes you may need to iterate through all the keys within an object. This requires a specific syntax in JavaScript called a *for...in* statement."
 - "**NOTE**: Objects do not maintain an ordering to stored keys like arrays do; thus a key's position on an object, or the relative order in which it appears, is irrelevant when referencing or accessing that key."
 - `Object.keys()` is a method will generate an array of all the keys within an objects. It takes an object as its argument.

**Thoughts:** Whew! Nested arrays and objects can be a bit dicey, but I think I'm getting there. It took a lot of brain power to navigate through them and write functions/code to manipulate the different levels.

I ended up doing a 'power' code session where I worked for two 33-minute blocks of time while listening to the Battlestar Galactica song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ). This 'power' session approached help me stay focus and complete the 'Basic Data Structure' section of the course which was great because that was my goal when I sat down to study.

I'm not sure I'd always take this approach (sitting for an hour with only a small break in the middle is taxing on the body and mind), but I wanted to get in my study time today since I've got some other plans (and chores) to this Sunday. That aside, I think today was another good study session and I'm looking forward to the next.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 15: August 20, 2022

**Today's Progress:** Today I started the [Basic Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-data-structures) of freeCodeCamp's course on JavaScript. Currently I am 45% complete. Today's challenges focused on mutating arrays using the methods `push()`, `unshift()`, `pop()`, `shift()`, `splice()`, `slice()`, and using the spread operator (`...`). Here are my notes from today's session:

*Quotes & Key Ideas:*
 - Arrays have a length property which can be accessed with the syntax `Array.length`
 - "**The fundamental feature of any data structure is, of course, the ability to not only store data, but to be able to retrieve that data on command.**"
 - In JavaScript, arrays are indexed starting at zero (`0`). Item within arrays can be accessed using *bracket* `[]` notation, for example `array[0]` accesses the first item in the array called `array`. Often, we will assign an element of an array to a variable for easy access (i.e., `element = array[0]`). We can also re-assign (i.e., replace) elements within an array using the bracket notation: `array[1] = "new element";` will re-assign the second element with the new string `"new element"`.
 - Arrays are *mutable* and can be modified using the methods of `push()` and `unshift()`. `push()` adds an element at the end of the array and `unshift()` adds an element at the beginning of the array. These methods can accept multiple arguments, including variables.
 - "Both `push()` and `unshift()` have corresponding methods that are *nearly* functional opposites: `pop()` and `shift()`. As you may have guessed by now, instead of adding, `pop()` removes an element from the end of an array, while `shift()` removes an element from the beginning. The key difference between `pop()` and `shift()` and their cousins `push()` and `unshift()`, is that neither method takes parameters, and **each only allows an array to be modified by a single element at a time**."
 - `splice()` allows us to remove any number of consecutive elements from anywhere in an array. This method can take up to 3 parameters; the first parameter represents the index of the array that `splice()` is being called upon, the second parameter (optional) represents the number of elements to delete, and the third parameter (optional) represents new elements to be added. "`splice()` not only modifies the array it's being called on, but it also returns a new array containing the value of the removed elements"
 - `slice()` copies or extracts a given number of elements to a new array, leaving the array it is called upon untouched. It "takes only 2 parameters — the first is the index at which to begin extraction, and the second is the index at which to stop extraction (**extraction will occur up to, but not including the element at this index**)"
 - "ES6's new *spread operator* allows us to easily copy all of an array's elements, in order, with a simple and highly readable syntax. The spread syntax simply looks like this: `...`" For example, `thatArray = [...thisArray]` will copy all of the elements from `thisArray` into a new array assigned to `thatArray`.

**Thoughts:** At the beginning of my coding session I was feeling a little sluggish and sleepy, but listening to the Battlestar Galactica song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) and using an interval timer helped me stay focused.

I really enjoyed today's challenges because they worked a lot of with arrays and indexing of arrays. I have a pretty solid understanding of how indexing works, but sometimes it takes a bit effort to wrap my head around it in practice. Today's challenges were full of practicing the indexing of arrays by adding and removing elements.

I also enjoyed some of the logic problems introduced with creating functions that copy arrays based on a given number. These problems are starting to make use of all the previous topics which is nice to see it all coming together. I would imagine it's similar to when you first start learning to read. Yeah, it's great to be able to write out letters and spell words, but it's not until you're able to read full books that you really get the benefit of all the writing practice.

Later in the afternoon, after completing freeCodeCamp's challenges, I read Chapter 4 'Data Structures: Objects and Arrays' from [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke. The coincidental alignment of this chapter with today's challenges was a convenient and advantageous to me. Reading the chapter helped solidify the ideas as well as provided some extra, deeper examples to further my understanding.

Overall, today's session felt great (even if I was a bit drained from the first week of school).

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 14: August 19, 2022

Rest Day.

### Day 13: August 18, 2022

**Today's Progress:** Today I finished the final challenges for the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section on freeCodeCamp AND I was able to complete the 12 challenges for the [Debugging](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#debugging). Here are my notes from today's session:

*Quotes & Key Ideas:*
- "You can search and replace text in a string using `.replace()` on a string. The inputs for `.replace()` is first the regex pattern you want to search for. The second parameter is the string to replace the match or a function to do something."
- Firefox and Chrome have DevTools to help with debugging JavaScript
- The `console.log()` method can be strategically placed at points within in your code so you know what's happening as the program is being run. This helps with knowing where to look when something goes wrong.
- `typeof` can be used to check the data structure/type of a variable
- "JavaScript recognizes seven primitive (immutable) data types: `Boolean`, `Null`, `Undefined`, `Number`, `String`, `Symbol` (new with ES6), and `BigInt` (new with ES2020), and one type for mutable items: `Object`. Note that in JavaScript, arrays are technically a type of object."

**Thoughts:** The syntax of the regular expressions can be a little tricky, but I think I'm getting the hang of it. I really enjoyed the debugging challenges. It was really useful to read the code in a program and know that there was an error somewhere. It reinforced some previous concepts of how everything fits together. It also felt a little bit like the coding version of *Where's Waldo?*. Overall, I felt great about today's session and I'm looking forward to learning about Basic Data Structures in JavaScript.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 12: August 17, 2022

**Today's Progress:** Today I worked on the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section (93% done so far). The main focuses of the challenges included different combinations of matching (e.g., matching everything, everything but numbers, everything but letters. etc.), positive and negative lookaheads, and checking for mixed groupings. Here are my notes from today's session:

*Quotes & Key Ideas:*
- "You can search for whitespace using `\s`, which is a lowercase `s`. This pattern not only matches whitespace, but also carriage return, tab, form feed, and new line characters."
- "Search for non-whitespace using `\S`, which is an uppercase `s`. This pattern will **not** match whitespace, carriage return, tab, form feed, and new line characters."
- "Quantity specifiers are used with curly brackets (`{` and `}`). You put two numbers between the curly brackets - for the lower and upper number of patterns. For example, to match only the letter a appearing between `3` and `5` times in the string `ah`, your regex would be `/a{3,5}h/`."
- "You can specify the possible existence of an element with a question mark, `?`. This checks for zero or one of the preceding element. You can think of this symbol as saying the previous element is optional."
- "*Lookaheads* are patterns that tell JavaScript to look-ahead in your string to check for patterns further along. This can be useful when you want to search for multiple patterns over the same string." *Positive lookaheads* look for a match while *negative lookaheads* look to see if there isn't a match.
- "Sometimes we want to check for groups of characters using a Regular Expression and to achieve that we use parentheses `()`. If you want to find either Penguin or Pumpkin in a string, you can use the following Regular Expression: `/P(engu|umpk)in/g`"

**Thoughts:** Yesterday, I was feeling pretty confident with the regexes but today the syntax seemed harder for my brain to process. I think I might need to practice them a bit more. However, I worked on this during the afternoon when I would have preferred to take a nap - it's the first week of school and I'm feeling the drain on my energy levels. With school starting I think I might need to adjust my goals a bit; instead of aiming for a full hour of code each day I think I might aim for 30 minutes. This will be easier to meet and if I have the energy (or momentum) I can always keep doing.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 11: August 16, 2022

**Today's Progress:** Today I worked on the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section (61% done so far). Today's challenges were all focused on using regular expressions to match strings of characters. Here are my notes from today's session:

*Quotes & Key Ideas:*
- You can use a flag to match different cases of regexes. For example, `/apple/i` will match all cases of the string 'apple' such as apple, Apple, aPPle, etc.
- "You can also extract the actual matches you found with the `.match()` method."
- "To search or extract a pattern more than once, you can use the global search flag: `g`"
- "You can have multiple flags on your regex like `/search/gi`"
- **Wildcard Charcter**: "The wildcard character `.` will match any one character. The wildcard is also called `dot` and `period`. You can use the wildcard character just like any other character in the regex. For example, if you wanted to match `hug`, `huh`, `hut`, and `hum`, you can use the regex `/hu./` to match all four words."
- **Match Single Character with Multiple Possibilities**: "For example, you want to match `bag`, `big`, and `bug` but not `bog`. You can create the regex `/b[aiu]g/` to do this. The `[aiu]` is the character class that will only match the characters `a`, `i`, or `u`."
- "Inside a character set, you can define a range of characters to match using a hyphen character: `-`. For example, to match lowercase letters `a` through `e` you would use `[a-e]`."
- "Using the hyphen (`-`) to match a range of characters is not limited to letters. It also works to match a range of numbers. For example, `/[0-5]/` matches any number between `0` and `5`, **including the `0` and `5`**."
- It's also possible to match both letters and numbers at the same time. For example, `/[h-s2-6]/` will match the letters `h` through `s` and the numbers `2` through `6`.
- **Negated characters** (characters you do NOT want to match): "To create a negated character set, you place a caret character (`^`) after the opening bracket and before the characters you do not want to match. For example, `/[^aeiou]/gi` matches all characters that are not a vowel. "
 - You can use the + character to check to match a character (or group of characters) that appears one or more times in a row. "For example, `/a+/g` would find one match in abc and return `["a"]`. Because of the `+`, it would also find a single match in aabc and return `["aa"]`."
 - While the `+` sign is used to check if a character occurs **one or more** times, the `*` sign can be used to check if a character occurs **zero or more** times.

 **Greedy vs. Lazy Matching**:
 - A *greedy* match will match the *longest* possible part of the string
 - A *lazy* match will match shortest possible part that satisfies the regex expression. However, you can use the `?` character to change it to lazy matching.
 - "*Note*: Parsing HTML with regular expressions should be avoided, but pattern matching an HTML string with regular expressions is completely fine."
 - You can also use the `^` carrot character to search the beginning of strings, but to search the end of a string you would use the `$` dollar symbol at the end (e.g., `/story$/` will look for the string `story` at the end of a string like `This is the end of the story` and return a `true` value)

 **shorthand character classes**:
 - *alphanumeric*: In JavaScript the shortcut `\w` is used in place of `[A-Za-z0-9_]` to search for alphanumeric characters.
 - *non-alphanumeric*: To search for the opposite of alphanumeric characters (i.e,. `!`, `%`, etc.) we can use `\W` which is equivalent to `[^A-Za-z0-9]`.
 - *digits 0-9*: The shortcut to look for digit characters is `\d`, with a lowercase `d`. This is equal to the character class `[0-9]`

**Thoughts:** Overall I'm feeling pretty confident about today's study session. The regular expressions haven't been too difficult for me, though I have seen them before in my study of Python - but that was a while ago so I'm appreciating the review in these challenges.

I didn't listen to music during today's session - my hour of coding was broken up in to small segments at work and at home. I squeezed in the time wherever I could which worked pretty well. There's something relaxing about working on coding challenges, it's a nice break from the 'day job'. Looking forward to learning more.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 10: August 15, 2022

Rest day.

### Day 9: August 14, 2022

**Today's Progress:** Today I COMPLETED the [ES6](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6) section of fCC's course 'JavaScript Algorithms and Data Structures' and started the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section (9% done so far). The ES6 section finished with challenges focused on module script, import/export, and promises. Here are my notes from today's session:

*Quotes & Key Ideas:*
- "*Template literals* allow you to create multi-line strings and to use string interpolation features to create strings." The are created using the following syntax: `${variable}` where `variable` is your desired output.
- **ES5** uses the keyword `function` while in **ES6**, you can remove the `function` keyword and colon altogether when defining functions in objects.
- "ES6 provides a new syntax to create objects, using the class keyword. It should be noted that the class syntax is just syntax, and not a full-fledged class-based implementation of an object-oriented paradigm, unlike in languages such as Java, Python, Ruby, etc."
- "UpperCamelCase should be used by convention for ES6 class names"
- "It is convention to precede the name of a private variable with an underscore (`_`). However, the practice itself does not make a variable private."

*A different syntax is used for importing default files*:

"To import a default export, you need to use a different import syntax. In the following example, add is the default export of the `math_functions.js` file. Here is how to import it:

`import add from "./math_functions.js";`

The syntax differs in one key place. The imported value, `add`, is not surrounded by curly braces (`{}`). `add` here is simply a variable name for whatever the default export of the `math_functions.js` file is. You can use any name here when importing a default."

**Thoughts:** I feel a lot of ES6 challenges are taken out of context, I'm hoping they'll make more sense as I progress and see how their used in practice. If not, then I'll need to study them in more detail. The template literals and regex (so far) were pretty straight forward to me - I've played around with regexes before in a Python course. Some of the shorthand syntax is a little weird and I'm struggling to wrap my mind around it, but I think with practice it'll sink in better.

For music today, I went back to the Battlestar Galactica song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) (on repeat to keep me focused).

Overall, I'm very satisfied with the progress I made today (especially since I completed a section of the course) and I'm looking forward to the next. I've still got 7 more sections to go until I get to the projects which are always 'fun' challenges because that's when you get to put it all together.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 8: August 13, 2022

**Today's Progress:** Today I started [ES6](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6) section of fCC's course 'JavaScript Algorithms and Data Structures'. I'm currently 48% complete with it. The majority of todays challenges focused on destructuring.

I also read through Chapter 3 'Functions' from [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke.

*Quotes & Key Ideas:*

`let` vs. `const`:
- "When you declare a variable with the `let` keyword inside a block, statement, or expression, its scope is limited to that block, statement, or expression"
- ""`const` has all the awesome features that let has, with the added bonus that variables declared using `const` are read-only. They are a constant value, which means that once a variable is assigned with const, it cannot be reassigned"
- "However, it is important to understand that objects (including arrays and functions) assigned to a variable using `const` are still mutable. Using the `const` declaration only prevents reassignment of the variable identifier"
- "To ensure your data doesn't change, JavaScript provides a function `Object.freeze()` to prevent data mutation."

`spread operator` vs. `array destructuring`:

"One key difference between the spread operator and array destructuring is that the spread operator unpacks all contents of an array into a comma-separated list. Consequently, you cannot pick or choose which elements you want to assign to variables. Destructuring an array lets us do exactly that."

**Thoughts:** The challenges on fCC were a little bit difficult today, especially the ones focused on destructuring. I will need to take another look at some of these or find some other resources to dive deeper into them.

Reading *Eloquent JavaScript* so far has been a useful method of review. The chapter I read today focused on functions and it was helpful to read about the theory of how these work and recall the work I did on the fCC's challenges which involved functions. For now, I'm going to continue to skip the exercises in the book and come back to them later. The combination of completing the challenges/exercises on fCC and reading the book chapters seems to be working well for me.

For music today, I plugged in my speakers and played some [Soft Piano Jazz](https://youtu.be/UnTbgByYZWA) and gave my room a bit of a cafe vibe - but without the loud espresso machine. (-;

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 7: August 12, 2022

**Today's Progress:** Today I completed the [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) section of the *JavaScript Algorithms and Data Structures* course created by freeCodeCamp. I finished up this first section by learning about generating random numbers, using the `parseInt()` function, and using recursion.

I also read through the first two chapters of [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke.

**Thoughts:** Today was productive day. First, I read a few chapters of *Eloquent JavaScript* which was a smart choice. Most of the content in the book (so far) is the same as what was been covered in the *Basic JavaScript* section of fCC's course, but in more depth. I'm appreciating the deeper explanations. I like the quick, straight-to-the-point explanations that come with fCC's challenges, but it's nice to get to know them with more detail. The book also has exercises and projects, but I might hold off on those until I complete the entire fCC course.

After reading I jumped into the final few challenges of the *Basic JavaScript*. I'm very satisfied with this progress and looking forward to tomorrow's coding challenges which start with the features of [ES6](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6).

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 6: August 11, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 91% complete with the course. Today's challenges focused on writing a function to look up names and properties in a contacts array.

**Thoughts:** I'm tired. I got home late after an after-work dinner with some colleagues. I only spent about 20 minutes (not a full hour, but better than nothing) on today's challenge. I was able to get a rough outline of the function complete, but my brain is too tired to think clearly through the logic loops on this one. I'll have to save it for tomorrow.

In looking for resources to help solve this problem, I stumbled upon the book [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke. I'm enjoying freeCodeCamp's guided challenges (which do get progressively harder), but I think this book will help me understand some of the theory on a deeper level. It also has some chapters that focus on a building projects which is something I enjoy. What's the point of learning new skills if you can create something after, right?

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 5: August 10, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 91% complete with the course - almost done! Today's challenges focused on iterations with loops. Here are some notes and key ideas I saved from today's session:

- `for` loops are declared with three optional expressions separated by semicolons:
`for (a; b; c)`, where `a` is the initialization statement, `b` is the condition statement, and `c` is the final expression
- a `do...while` loop because it will first do one pass of the code inside the loop no matter what, and then continue to run the loop `while` the specified condition evaluates to `true`
 - Essentially, a `do...while` loop ensures that the code inside the loop will run at least once

**Thoughts:**  This was a good review lesson for me - both of the mathematics involved in the loops and the loops themselves. I've previously taken a Python programming course so I was familiar with the concepts of loops, but in JavaScript the syntax and setup is a little different so it was good to get that experience.

I switched up my music today. I was feeling a little sleepy so I decided to listen to something a with a little more pep in it. I really enjoy the use of drum beats and string instruments in this song from the Battlestar Galactica (2005 reboot) *Prelude to War* composed by Bear McCreary:

- [Studio recorded version](https://youtu.be/K2RQvE0GfYQ)
- [Live performance](https://youtu.be/NohlZt1NB0g)
- [Scene from the show featuring the song](https://youtu.be/J4PoBrrp6bY)

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 4: August 9, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 84% complete with the course. Today's challenges focused on using objects for lookups, testing/manipulating objects, and accessing nested objects and arrays.

**Thoughts:**  I'm not sure if these challenges were more difficult for me or if I was just tired, but I had to look things up and get some hints to make it through. It made me progress more slowly than I would have liked, but I'm okay with that - I don't want to go too quickly. Most of my troubles or 'road blocks' today came from minor typos (yay syntax errors!) and forgetting little things like '==' vs. '==='. Again, I'm not sure if it's because I'm tired or if I need some review, but a little review of the basics couldn't hurt.  

I continued listening to [Vivaldi's 'Four Seasons - Winter'](https://youtu.be/ZPdk5GaIDjo) on repeat to help me focus AND I used an interval timer so that I would get up and move every 20 minutes, instead of sitting for an entire hour.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 3: August 8, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 79% complete with the course.

**Thoughts:** Today went smoothly. I needed to look up a few things for reference (e.g., the syntax of a switch statement), but other than that I had no issues.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 2: August 7, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 71% complete with the course.

**Thoughts:** Sadly, I had to cut my study session short because I had a headache which was making staring at screen (and problem-solving) difficult, but I'm still happy I got a quick session in to complete a few challenges. Again, while coding I listened to [Vivaldi's 'Four Seasons - Winter'](https://youtu.be/ZPdk5GaIDjo) on repeat which helped me focus.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 1: August 6, 2022

**Today's Progress:** Continued working on [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript) course created by freeCodeCamp. Currently 66% complete with the course. Challenges went smoothly today.

**Thoughts:** I felt pretty good about today's study session. I did it first thing in the morning so I was more alert which helped a lot. So far the JavaScript isn't too challenging; it's been a good review of the math concepts and the programming concepts (I've previously studied Python Programming). Again, while coding I listened to [Vivaldi's 'Four Seasons - Winter'](https://youtu.be/ZPdk5GaIDjo) on repeat which helped me focus. Setting a time for an hour also helps, though next time I think I might use an interval timer so that I take short breaks during the hour to stand up and stretch.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 0: August 5, 2022

**Today's Progress:** Started working on Basic JavaScript course created by freeCodeCamp. Currently 34% complete with the course. Got stuck on the 'Word Blanks' activity but after staring at it for several minutes, having my partner look at it, I finally found the answer in a [forum](https://forum.freecodecamp.org/t/word-blanks-hey-guys-i-need-help-i-cant-seem-to-get-this-right-i-have-passed-all-the-words-into-word-blanks-but-its-still-not-right/225558/8?u=codebyfifi). My error was syntactical and I forgot to include spaces before AND after the variables in the concatenated string.

**Thoughts:** Next time I think I need to work a little earlier in the evening. I worked 8pm-9pm and my brain was tired which made reading on a screen (and understanding some instructions) difficult. I did however listen to [Vivaldi's 'Four Seasons - Winter'](https://youtu.be/ZPdk5GaIDjo) on repeat which helped me focus.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).
