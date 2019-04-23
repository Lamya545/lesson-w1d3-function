For all the questions below, test them with different values being passed into the function.  Do this all in lab-1.js.



### A. `printGreeting`

Do you think you could write a function called `printGreeting` with a parameter `name` that returns a greeting with the argument **interpolated** into the greeting?

Like so?

```javascript
console.log(printGreeting("Slimer"));
```
> `=> Hello there, Slimer!`

You think you could? I think so too. Feel free to skip this problem, because you've already done it. If you've done the problem twice, **read entire problems carefully before doing them from now on**.  



### B. `printCool`

Write a function `printCool` that accepts one parameter, `name` as an argument. The function should print the name and a message saying that that person is cool.

```javascript
console.log(printCool("Captain Reynolds"));
```

> `=> "Captain Reynolds is cool";`



### C. `calculateCube`

Write a function `calculateCube` that takes a single number and prints the volume of a cube made from that number.

```javascript
console.log(calculateCube(5));
```

> => 125



### D. `isVowel`

Write a function `isVowel` that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise. The vowel could be upper or lower case.  **Test your function on every vowel and make sure it's working.**  In general, when you write functions, take a minute to test them with different values to make sure they behave the way you want. 

```javascript
console.log(isVowel("a"));
```

> `=> true`



### E. `getTwoLengths`

Write a function `getTwoLengths` that accepts two parameters (strings). The function should **return** an _array_ of numbers where each number is the length of the corresponding string.

```javascript
console.log(getTwoLengths("Hank", "Hippopopalous"));
```
> `=> [4, 13]`



### F. `getMultipleLengths`

Write a function `getMultipleLengths` that accepts a single parameter as an argument: an **array** of **strings**. The function should **return** an **array** of **numbers** where each number is the length of the corresponding string.

```javascript
console.log(getMultipleLengths(["hello", "what", "is", "up", "dude"]));
```

> `=> [5, 4, 2, 2, 4]`



### G. `maxOfThree`

Define a function `maxOfThree` that takes three numbers as arguments and returns the largest of them. If all numbers are the same, it doesn't matter which one is returned. If the two largest numbers are the same, one of them should be returned.  Be sure to test it with larger values in each of the three locations.  

```javascript
console.log(maxOfThree(6, 9, 1));
```

> => 9

Did you use Google and find `Math.max()`?  If so, great job! Very resourceful—keep looking stuff up!  However, for this particular question, we need you to submit a solution that **does not** use `Math.max()`.



### H. `printLongestWord`

Write a function `printLongestWord` that accepts a single argument, an **array** of **strings**. The method should return the longest word in the array. In case of a tie, the method should return the word that appears first in the array.

```javascript
console.log(printLongestWord(["BoJack", "Princess", "Diane", "a", "Max", "Peanutbutter", "big", "Todd"]));
```

> `=> "Peanutbutter"`



### I. `transmogrify`

Write a Javascript function called `transmogrify`. This function should accept three arguments, which you can assume will be numbers. Your function should return the "transmogrified" result.

The transmogrified result of three numbers is the product of the first two numbers, raised to the power of the third number.

For example, the transmogrified result of 5, 3, and 2 is `(5 times 3) to the
power of 2` is 225.

```javascript
console.log(transmogrify(5, 3, 2));
```
> `=> 225`


