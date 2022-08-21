# 100 Days Of Code - Log
For regular updates follow me on Twitter [@wordsbyfifi](https://twitter.com/wordsbyfifi/) or visit my blog on [Medium](https://anthonynanfito.medium.com/) to read the 'pretty' version this log.

### Day 16: August 21, 2022

**Today's Progress:** Today I completed the second half of the [Basic Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-data-structures) section on JavaScript course from freeCodeCamp. Next, I'll be moving on to 'Basic Algorithm Scripting'. Today's challenges focused on interacting with nested arrays and objects. Below are my notes and reflection from today's session.

*Quotes & Key Ideas*:
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

I ended up doing a 'power' code session where I worked for two 33-minute blocks of time while listening to the Battlestar Galactic song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ). This 'power' session approached help me stay focus and complete the 'Basic Data Structure' section of the course which was great because that was my goal when I sat down to study.

I'm not sure I'd always take this approach (sitting for an hour with only a small break in the middle is taxing on the body and mind), but I wanted to get in my study time today since I've got some other plans (and chores) to this Sunday. That aside, I think today was another good study session and I'm looking forward to the next.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 15: August 20, 2022

**Today's Progress:** Today I started the [Basic Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-data-structures) of freeCodeCamp's course on JavaScript. Currently I am 45% complete. Today's challenges focused on mutating arrays using the methods `push()`, `unshift()`, `pop()`, `shift()`, `splice()`, `slice()`, and using the spread operator (`...`). Here are my notes from today's session:

*Quotes & Key Ideas*:
 - Arrays have a length property which can be accessed with the syntax `Array.length`
 - "**The fundamental feature of any data structure is, of course, the ability to not only store data, but to be able to retrieve that data on command.**"
 - In JavaScript, arrays are indexed starting at zero (`0`). Item within arrays can be accessed using *bracket* `[]` notation, for example `array[0]` accesses the first item in the array called `array`. Often, we will assign an element of an array to a variable for easy access (i.e., `element = array[0]`). We can also re-assign (i.e., replace) elements within an array using the bracket notation: `array[1] = "new element";` will re-assign the second element with the new string `"new element"`.
 - Arrays are *mutable* and can be modified using the methods of `push()` and `unshift()`. `push()` adds an element at the end of the array and `unshift()` adds an element at the beginning of the array. These methods can accept multiple arguments, including variables.
 - "Both `push()` and `unshift()` have corresponding methods that are *nearly* functional opposites: `pop()` and `shift()`. As you may have guessed by now, instead of adding, `pop()` removes an element from the end of an array, while `shift()` removes an element from the beginning. The key difference between `pop()` and `shift()` and their cousins `push()` and `unshift()`, is that neither method takes parameters, and **each only allows an array to be modified by a single element at a time**."
 - `splice()` allows us to remove any number of consecutive elements from anywhere in an array. This method can take up to 3 parameters; the first parameter represents the index of the array that `splice()` is being called upon, the second parameter (optional) represents the number of elements to delete, and the third parameter (optional) represents new elements to be added. "`splice()` not only modifies the array it's being called on, but it also returns a new array containing the value of the removed elements"
 - `slice()` copies or extracts a given number of elements to a new array, leaving the array it is called upon untouched. It "takes only 2 parameters — the first is the index at which to begin extraction, and the second is the index at which to stop extraction (**extraction will occur up to, but not including the element at this index**)"
 - "ES6's new *spread operator* allows us to easily copy all of an array's elements, in order, with a simple and highly readable syntax. The spread syntax simply looks like this: `...`" For example, `thatArray = [...thisArray]` will copy all of the elements from `thisArray` into a new array assigned to `thatArray`.

**Thoughts:** At the beginning of my coding session I was feeling a little sluggish and sleepy, but listening to the Battlestar Galactic song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) and using an interval timer helped me stay focused.

I really enjoyed today's challenges because they worked a lot of with arrays and indexing of arrays. I have a pretty solid understanding of how indexing works, but sometimes it takes a bit effort to wrap my head around it in practice. Today's challenges were full of practicing the indexing of arrays by adding and removing elements.

I also enjoyed some of the logic problems introduced with creating functions that copy arrays based on a given number. These problems are starting to make use of all the previous topics which is nice to see it all coming together. I would imagine it's similar to when you first start learning to read. Yeah, it's great to be able to write out letters and spell words, but it's not until you're able to read full books that you really get the benefit of all the writing practice.

Later in the afternoon, after completing freeCodeCamp's challenges, I read Chapter 4 'Data Structures: Objects and Arrays' from [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke. The coincidental alignment of this chapter with today's challenges was a convenient and advantageous to me. Reading the chapter helped solidify the ideas as well as provided some extra, deeper examples to further my understanding.

Overall, today's session felt great (even if I was a bit drained from the first week of school).

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 14: August 19, 2022

Rest Day.

### Day 13: August 18, 2022

**Today's Progress:** Today I finished the final challenges for the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section on freeCodeCamp AND I was able to complete the 12 challenges for the [Debugging](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#debugging). Here are my notes from today's session:

*Quotes & Key Ideas*:
- "You can search and replace text in a string using `.replace()` on a string. The inputs for `.replace()` is first the regex pattern you want to search for. The second parameter is the string to replace the match or a function to do something."
- Firefox and Chrome have DevTools to help with debugging JavaScript
- The `console.log()` method can be strategically placed at points within in your code so you know what's happening as the program is being run. This helps with knowing where to look when something goes wrong.
- `typeof` can be used to check the data structure/type of a variable
- "JavaScript recognizes seven primitive (immutable) data types: `Boolean`, `Null`, `Undefined`, `Number`, `String`, `Symbol` (new with ES6), and `BigInt` (new with ES2020), and one type for mutable items: `Object`. Note that in JavaScript, arrays are technically a type of object."

**Thoughts:** The syntax of the regular expressions can be a little tricky, but I think I'm getting the hang of it. I really enjoyed the debugging challenges. It was really useful to read the code in a program and know that there was an error somewhere. It reinforced some previous concepts of how everything fits together. It also felt a little bit like the coding version of *Where's Waldo?*. Overall, I felt great about today's session and I'm looking forward to learning about Basic Data Structures in JavaScript.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 12: August 17, 2022

**Today's Progress:** Today I worked on the [Regular Expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions) section (93% done so far). The main focuses of the challenges included different combinations of matching (e.g., matching everything, everything but numbers, everything but letters. etc.), positive and negative lookaheads, and checking for mixed groupings. Here are my notes from today's session:

*Quotes & Key Ideas*:
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

*Quotes & Key Ideas*:
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

*Quotes & Key Ideas*:
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

For music today, I went back to the Battlestar Galactic song [*Prelude to War*](https://youtu.be/K2RQvE0GfYQ) (on repeat to keep me focused).

Overall, I'm very satisfied with the progress I made today (especially since I completed a section of the course) and I'm looking forward to the next. I've still got 7 more sections to go until I get to the projects which are always 'fun' challenges because that's when you get to put it all together.

**Link to work:** For my progress visit the timeline on my [freeCodeCamp Profile](https://www.freecodecamp.org/ananfito).

### Day 8: August 13, 2022

**Today's Progress:** Today I started [ES6](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6) section of fCC's course 'JavaScript Algorithms and Data Structures'. I'm currently 48% complete with it. The majority of todays challenges focused on destructuring.

I also read through Chapter 3 'Functions' from [*Eloquent JavaScript*](https://eloquentjavascript.net/) by Marjin Haverbeke.

*Quotes & Key Ideas*:

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

I switched up my music today. I was feeling a little sleepy so I decided to listen to something a with a little more pep in it. I really enjoy the use of drum beats and string instruments in this song from the Battlestar Galactic (2005 reboot) *Prelude to War* composed by Bear McCreary:

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
