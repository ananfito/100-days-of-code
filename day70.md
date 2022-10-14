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
