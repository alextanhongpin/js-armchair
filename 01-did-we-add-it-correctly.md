# Did we add it up correctly?


This is the first JavaScript bi-monthly post. 

And it's about addition! Let's do some addition with JavaScript.

We are gonna write an `add` function that sums two `integer`, and return the `integer` sum.

```javascript
add(1, 2) // returns 3
add(20, 30) // returns 50
...
```

It's easy right? Now write the code. Convinced that you have done it correctly? 

Now let's test!

```javascript
add(1, 2) // returns 3
add(-10, 10) // returns  0
add('1', 2) // returns 3
add(1, '-20') // returns -19
add(true, 1) // throws error
add('a', 'b') // throws error
add(null, undefined) // throws error
add(true, false) // throws error
add(1) // throws error
add(true) // throws error
add('a') // throws error
add('100') // throws error
```

If you pass all the test and would like to share your solutions to us, submit it to us.