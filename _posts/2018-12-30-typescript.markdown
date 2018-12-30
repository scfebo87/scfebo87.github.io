---
layout: post
title:      "TypeScript"
date:       2018-12-30 22:46:46 +0000
permalink:  typescript
---


In a previous post I wrote about CoffeScript, a language that compiles into JavaScript. TypeScript is another option people use and is getting popular. TypeScript was developed by Microsoft and is a superset of JavaScript. This means that any valid JavaScript is also valid for TypeScript. Like CoffeScript, it has it's own website where you can find some great documentation to get started. I would recommend checking out the 5 minute tutorail that walks you through building a web application with TypeScript in 5 minutes:

https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html

The site also has a playground to learn and practice:

https://www.typescriptlang.org/play/index.html

Here is a very small example of TypeScript:

```
var message:string = "Hello World" 
console.log(message)
```

This complies to JavaScript:
```
var message = "Hello World";
console.log(message);
```

This small example does not show big differences except the variable decalres with the keyword 'string'. TypeScript uses 'type annotations' to record the intended contract of the variable(or function).
