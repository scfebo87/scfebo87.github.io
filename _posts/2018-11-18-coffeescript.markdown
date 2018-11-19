---
layout: post
title:      "CoffeeScript"
date:       2018-11-19 00:17:56 +0000
permalink:  coffeescript
---


Now that I have finished my program I am starting to dive into some topics outside Ruby, Vanilla JS, and React. Something we touched on a little in the program, but have decided to look into more lately is CoffeScript. Here is how CoffeeScript is defined by their website: 

"CoffeeScript is a little language that compiles into JavaScript. [It] is an attempt to expose the good parts of JavaScript in a simple way." 

In other words, CoffeScript tries to make writing Javascript easier by giving you a more readable way to code. After writing your code in .coffee files, they are then compiled into .js files. CoffeeScript does need be installed which you can do globally by npm install -g coffee-script. Here are some examples of CoffeScript. As you will see, "coffee" uses less code and reads more like english. These examples again come from coffeescript.org. First the CoffeeScript:

```
# Assignment:
number   = 42
opposite = true

# Conditions:
number = -42 if opposite

# Functions:
square = (x) -> x * x

# Arrays:
list = [1, 2, 3, 4, 5]

# Objects:
math =
  root:   Math.sqrt
  square: square
  cube:   (x) -> x * square x

# Splats:
race = (winner, runners...) ->
  print winner, runners

# Existence:
alert "I knew it!" if elvis?

# Array comprehensions:
cubes = (math.cube num for num in list)
```

This becomes the javascript we know: 
 
 ``
// Assignment:
var cubes, list, math, num, number, opposite, race, square;

number = 42;

opposite = true;

if (opposite) {
  // Conditions:
  number = -42;
}

// Functions:
square = function(x) {
  return x * x;
};

// Arrays:
list = [1, 2, 3, 4, 5];

// Objects:
math = {
  root: Math.sqrt,
  square: square,
  cube: function(x) {
    return x * square(x);
  }
};

// Splats:
race = function(winner, ...runners) {
  return print(winner, runners);
};

if (typeof elvis !== "undefined" && elvis !== null) {
  // Existence:
  alert("I knew it!");
}

// Array comprehensions:
cubes = (function() {
  var i, len, results;
  results = [];
  for (i = 0, len = list.length; i < len; i++) {
    num = list[i];
    results.push(math.cube(num));
  }
  return results;
})();
``

Learning CoffeScript is almost like learning a brand new language in some ways, so I'm not convinced of switiching completely from the vanilla JavaScript I already know, however if you hate using semi-colons and curly braces, then this might be the way to go. 

