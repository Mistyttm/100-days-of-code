# Notes

### Day 19 4/11/21
**Notes:** 
  *  ``let`` allows for variables with the same name to exist within multiple functions
  *  ``const`` is not mutable
      *  ``const s = [1, 2, 3, 4]`` cannot be reassigned with ``s = [1, 2, 4]``
      *  ``s[1] = 45`` will however allow for that index to be mutated
  *  ``Object.freeze()`` is a function that completely stops objects from being altered.
      * If an editor is running in strict mode, an error will be thrown to the console
  *  Arrow notation allows for functions that are not going to be reused to be shortened down within a variable
      *  it allows for the ``return`` method to be skipped entirely
      *  eg: ``const i = () => "value";``


### Day 20 5/11/21
**Notes:**
  *  arrow notation can also have variables used
      *  eg: `const myConst = item => item *2;`
  *  the variables can have default values if nothing is passed through the function
  *  the rest parameter allows functions to be parsed with any number of arguments (`...`)
  *  the spread parameter looks the same to the rest parameter but spreads out an array for use in another variable
  *  ES6 allows for destructuring assignment.
      *  instead of multiple calls to an object, it can be done in one line
      *  ``const {name, age} = user`` would produce the name and age of the object ``user``
  *  within the destructured object, you can assign the values to new variables so that their values can be called later on in the code.


### Day 21 6/11/21
**Notes:**
  *  the destructured objects can also assign variable to nested objects in the same way
  *  destructured arrays work in a similar way to destructuring objects
  *  array elements can be reassigned using the rest parameter
  *  destructuring can also be done when being parsed through a function
  *  template literals use the backtick character in order to allow for multi line strings that can also contain variable outputs
      *  useful for iterating through arrays
  *  ES6 allows for declaring functions without using the ``function()`` keyword
  *  class syntax allows for the creation of constructer functions
  *  getters and setters allow for private variables to be manipulated by the user without them having direct access to the internals


### Day 22 7/11/21
**Notes:**
  *  javascript can be directly copmbined with HTML using the `<script></script>` tags
  *  JS functions can be exported for use in other JS files using the `export` keyword
      *  `export function() {code}`
      *  `export { function1, function 2 }`
  *  the `import` keyword has a similar syntax to the `export` keyword, and allows for exported functions to be imported from files.
  *  the wildcard character can also be used with the `import` keyword
  *  `export default` is used for making the fallback value of a file
  *  importing default functions does not require curly braces and the variable name for the function can be anything
  *  a promise is used to make a promise to do something asynchronously to the program
  *  there are three promise states:
      *  `pending`
      *  `resolved`
      *  `rejected`
  *  `then` is used when an asynchronous process has completed and you want to do something with the result
  *  `catch` is used when a promise outputs a `reject` has the same syntax to `then`


### Day 23 8/11/21
**Notes:**
  *  regular expressions are used to find secions of strings
  *  `.test()` returns a true or false
  *  regex is case sensitive
  *  the OR (`|`) operator can be used to find multiple strings
  *  adding `i` after the regex forces it to ignore case
  *  `.match()` can be used to return the exact string
  *  `g` is used to loop through the string to find all instances of the regex
  *  the wildcard character `.` is used to match anything in the string
  *  character classes, `[ ]`, allow for finding of specific characters within strings, like vowels
  *  the hyphen character `-` can be used to find a range of characters
      *  `[a-e]`
      *  works for numbers as well
      *  can be chained
          *  `[h-s2-6]`
  *  a carrat can be placed before the character set to make it a negated character set
      *  `[^aeiou]`
  *  `+` allows for searching of multiple instances of a character
