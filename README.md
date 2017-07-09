## What I learned in this module

1. This tutorial uses ES6 syntax which is much better than ES5 syntax
1. Babel is a compiler that transforms ES6 code into ES5 code using the Babel CLI
1. A `template string` is an ES6 feature that lets us inject variables directly inside the string without concatenation using ${}. *Note that template strings are created using backquotes.*
1. `babel` compiles ES6 files into new ES5 files
1. `babel-node` to execute ES6 files directly on the fly without compile. It is great for development but it is heavy and not meant for production. 
1. .babelrc is a JSON file for your Babel configuration
1. ES6: The most significant improvement of the JavaScript language
1. ESLint is the linter of choice for ES6 code. A linter gives you recommendations about code formatting, which enforces style consistency in your code, and code you share with your team.  ESLint can be configured in Intellij with a plugin
1. JavaScript has this thing called Automatic Semicolon Insertion, which allows you to write your code with or without semicolons.
1. Compat is a neat ESLint plugin that warns you if you use some JavaScript APIs that are not available in the browsers you need to support
1. Flow: A static type checker by Facebook. It detects inconsistent types in your code.  Type checking in your code will help you write code with less defects.  In Intellij set the *JavaScript Language Version* to Flow to get immediate feedback in Intellij if there is an error.
1. Jest: A JavaScript testing library by Facebook.  Also provides test code coverage
1. Git Hooks: Scripts that are run when certain actions like a commit or a push occur using Husky
