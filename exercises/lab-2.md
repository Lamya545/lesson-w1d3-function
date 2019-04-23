Answer the questions below the following code snippet. The letters in the questions and answer choices reference lines in the snippet.

```js
/* A */
var username = "XxXskaterBoi2004XxX"
/* B */
function logIn () {
    /* C */
    var sessionID = "8675309"
    /* D */
    return decrypt(sessionID)
    /* E */
    function decrypt (string) {
        /* F */
        var token = profileID
        /* G */
    }
    /* H */
}
/* I */
logIn()
/* J */
var profileID = 4011989
/* K */
```

1. The variable `username` **has a value** on which lines? (That is: on which lines will `console.log`ing it not return `undefined`?)
    - A, B, I, J, K
    - A and B
    - All lines
    - All lines except A
2. The variable `profileID` **has a value** on which lines?
    - A, B, I, J, K
    - K
    - All lines
    - All lines except A
3. The variable `profileID` **is accessible** on which lines? (That is: on which lines can it be `console.log`ged without throwing an error?)
    - A, B, I, J, K
    - K
    - All lines
    - All lines except A
4. The variable `sessionID` **is accessible** on which lines?
    - C, D, E, F, G, H
    - C, D, E, H
    - All lines
    - All lines except F and G
5. The function `decrypt` **is accessible** on which lines?
    - C, D, E, F, G, H
    - C, D, E, H
    - All lines
    - All lines except F and G

<details>

  <summary><strong>When you've finished...</strong></summary>

  1. All lines except A. The variable is available on all lines due to hoisting, but it only has a value after `username =`
  2. K. The variable is available on all lines due to hoisting, but it only has a value after `profileID =`
  3. All lines.
  4. C, D, E, F, G, H
  5. C, D, E, F, G, H

</details>
