# 100 Days Of Code - Log
Welcome to my journal for the [#100DaysOfCode challenge](https://www.100daysofcode.com/). Each day during the challenge I log my progress and my thoughts. If you'd like to learn, connect, and grow with me, follow me on [Twitter](https://twitter.com/wordsbyfifi/), [LinkedIn](https://linkedin.com/in/anthonynanfito), [Hashnode](https://ananfito.hashnode.dev/), or [DEV](https://dev.to/ananfito). Thanks for stopping by. Happy Coding!

## Contents

- [Latest Entry](#latest-entry)
- [Previous Entries](#previous-entries)

## Latest Entry

### Day 70: October 14, 2022

**Today's Progress:** I continued working [Intermediate Algorithm Scripting](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#intermediate-algorithm-scripting) challenges on freeCodeCamp; 57% complete.

*Quotes & Key Ideas:*

- `Array.filter()` is similar to a `for` loop and an `if` statement *combined*. In particular, when the arrow function `=>` is used the piece to the left of the `=>` is the piece that will be iterated over the array and the piece to the right of the `=>` is the `if` statement (or condition for which the filter is selecting). For example, `arr.filter(element => element % 2 !== 0)` filters all elements in the array `arr` that are odd. The first `element` refers to the elements in the array `arr` and will iterate through all of them (as dictated by the `filter` method) while the statement `element % 2 !== 0` is telling the `filter` method to select only the odd numbers from the array `arr`.

**Thoughts:** During today's session I think I stumbled upon a strategy to help me further my understanding. After stewing in frustration, I decided to consult the challenge guide and a tutorial for the challenge I found on YouTube - both have solutions to the challenge. However, I deliberately chose not to (initially) look at the solutions from the guide and tried to focus on the hints.

After a failed attempted to implement the hints, I consulted the YouTube tutorial video I found. I appreciated the explanation of the why and how certain methods are being used to solve the problem. That's really helpful as a beginner. Unfortunately the solution in the video was a few years old (it created an infinite loop so it's no longer valid) and doesn't pass the tests.

HOWEVER, the video's solution made use of the `filter` and `reduce` methods - methods I previously struggled with - and helped explain them in context. This was extremely helpful and a light bulb moment for me because I have been avoiding using the methods whenever possible since they didn't make much sense to me. Now they do which is great. In particular (as outlined above) I have a better understanding of how the `filter` and arrow function `=>` work. The analogy to a `for` loop and `if` statement helped clarify things in my head.

Finally, what ultimately helped me figure out the solution to this challenge was looking at the solution and deconstructing it. By that I mean not simply copying and pasting it into to pass the tests, but take it apart to identify what each section and method is doing to solve the challenge. Further, [this freeCodeCamp forum comment on an alternative solution](https://forum.freecodecamp.org/t/fibonacci-sums-using-array-filter-and-array-reduce/437062/2) helped me understand why my original solution was not working (or rather was inefficient) since it made use of arrays. This is only one opinion and I'm sure others may disagree, but it helped me see why in [the solution in freeCodeCamp's Challenge Guide](https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-sum-all-odd-fibonacci-numbers/16084) did *not* make use of an array.

Strangely, today's study session was brief but I probably learned more in it than I have in any of the previous study sessions this past week.

*Study Music:* [Battlestar Galactica's Prelude to War by Bear McCreary](https://youtu.be/4f2MnaV_j0Q)

*References:*

- [`while`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [`do...while`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while)
- [`forEach()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
- [freeCodeCamp Challenge Guide: Sum All Odd Fibonacci Numbers](https://forum.freecodecamp.org/t/freecodecamp-challenge-guide-sum-all-odd-fibonacci-numbers/16084)
- [YouTube Tutorial: freeCodeCamp Sum All Odd Fibonacci Numbers](https://youtu.be/dT_q5zcUAxQ)
- [Addition assignment `=+`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition_assignment)

**Link to work:** [freeCodeCamp Timeline](https://www.freecodecamp.org/ananfito)

## Previous Entries

- [Days 0–45: August 8 - September 19](./days0-45.md)
- [Day 46: September 20, 2022](./day46.md)
- [Day 47: September 21, 2022](./day47.md)
- Day 48: Rest Day
- Day 49: Rest Day
- [Day 50: September 24, 2022](./day50.md)
  - [Day 50: Reflecting at the Halfway Point](./day50-reflection.md)
- [Day 51: September 25, 2022](./day51.md)
- [Day 52: September 26, 2022](./day52.md)
- [Day 53: September 27, 2022](./day53.md)
- [Day 54: September 28, 2022](./day54.md)
- [Day 55: September 29, 2022](./day55.md)
- Day 56: Rest Day
- Day 57: Rest Day
- [Day 58: October 2, 2022](./day58.md)
- [Day 59: October 3, 2022](./day59.md)
- [Day 60: October 4, 2022](./day60.md)
- [Day 61: October 5, 2022](./day61.md)
- [Day 62: October 6, 2022](./day62.md)
- Day 63: Rest Day
- [Day 64: October 8, 2022](./day64.md)
- Days 65 - 68: Rest Days
- [Day 69: October 13, 2022](./day69.md)
- [Day 70: October 14, 2022](./day70.md)
