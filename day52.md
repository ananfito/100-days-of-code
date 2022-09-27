### Day 52: September 26, 2022

**Today's Progress:** I continued working [Intermediate Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#intermediate-algorithm-scripting) challenges on freeCodeCamp; 24% complete

*Quotes & Key Ideas:*

- Regular expressions:
  - `\s` matches a whitespace Character
  - `|` acts as the 'or' operator
  - `?=` is the positive lookahead
    - "If that particular element is present then the regex declares the match as a match otherwise it simply rejects that match."
    - `/a(?=r)` will match the `ar` in `car`, `bar`
  - `?!` is the negative lookahead
    - "If that particular element is not present then the regex declares the match as a match otherwise it simply rejects that match."
    - `/a(?!r)` will match everything but `ar` such as `ab`, `ad`, `ac`

**Thoughts:** I'm continuing to struggle with the regular expressions. The RegExr site is helping getting a better handle of the syntax for matching things, but I'm struggling with how to put them into use. In particular, I've been working the Pig Latin challenge on freeCodeCamp for two days now. I'm struggling with getting all the pieces together. I have consulted the MDN documentation as well as the solutions on freeCodeCamp's website.

The way I initially setup the function is very different than the solutions. I'm not sure that it's won't work, but I think I need to restructure my function. However, this is another example of how I'm stuck thinking about the particular solution to something and I'm not sure if I need more practice or something else.

*Study Music:* [Battlestar Galactica's Prelude to War by Bear McCreary](https://youtu.be/4f2MnaV_j0Q)

*References:*

- [`toLowerCase()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase)
- [Character classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Character_Classes)
- [`join()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join)
- [Learn Regular Expressions In 20 Minutes](https://youtu.be/rhzKDrUiJVk)
  - [RegExr](https://regexr.com/)
- [Regex Lookahead](https://regextutorial.org/positive-and-negative-lookahead-assertions.php)
- [`charAt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt)
- [`test()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)
- [`split()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)
- [Pig Latin solution](https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-pig-latin/16039)

**Link to work:** [freeCodeCamp Timeline](https://www.freecodecamp.org/ananfito)
