### Day 53: September 27, 2022

**Today's Progress:** I continued working [Intermediate Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#intermediate-algorithm-scripting) challenges on freeCodeCamp; 29% complete

*Quotes & Key Ideas:*

- In regular expressions, the carrot symbol `^` is used for both to check the beginning of a string **OR** to check the negation. For example, `/^[aeiou]/` checks for a vowel at the beginning of the string while `/[^aeiou]/` checks for *no* vowels. To check for a non-vowel character at the beginning of a string we would use `/^[^aeiou]/`.
- Apparently, you can uses multiple `replace()` methods together to sequential check and replace for certain matches like in the Pig Latin challenge from freeCodeCamp (e.g., `str.replace(/(^[aeiou]+\w*)/, "$1way").replace(/(^[^aeiou]+)(\w*)/, "$2$1ay");`).

**Thoughts:** Today's study session was focused primarily on trying to understand regular expressions. I think I'm starting to get them, but not really sure. I had to go through a lot of documentation, trial and error, and tutorials to find a solution to the Pig Latin scripting challenge. In the end, watching a tutorial helped me understand not only the solution but how the regular expressions work within it. This is primarily because the tutorial explained the thinking behind the solution.

This was extremely helpful to me because even after I finally gave up and read the solution on freeCodeCamp I still didn't understand it. But watching the video and seeing the thinking process that went into selecting the correct regex was extremely helpful to me. This is a strategy I'll have to remember in the future when I'm struggling and feel like banging my head up against a wall: find a tutorial that explains the thinking behind it (because banging your head on a wall is not helpful).

I would have liked to study more and complete another challenge, but since it's a work day I just don't have the time (or the energy). However, I am happy that I completed the Pig Latin challenge *and* I understand how the regex was chosen and how it fits into the overall solution. In short, it was a frustrating study session, but I'm glad I made some progress. I think for the remainder of this section of the course I'll have to aim for completing one challenge per day (especially on work days) otherwise I think I put too much pressure on myself. This also aligns with the goals I outlined in my [Day 50 reflection post](https://ananfito.hashnode.dev/day-50-reflecting-at-the-halfway-point).

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
  - [Video tutorial explaining the Pig Latin solution](https://youtu.be/q6haL-eNVqI)
- [`replace()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)

**Link to work:** [freeCodeCamp Timeline](https://www.freecodecamp.org/ananfito)
