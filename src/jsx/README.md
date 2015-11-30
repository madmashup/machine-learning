# JSX File(s)

Corresponding [jsx](https://facebook.github.io/react/docs/jsx-in-depth.html)
 template file(s) in this directory, will be converted from jsx to javascript
 syntax, using [browserify](http://browserify.org/), and the
 [babelify](https://babeljs.io/) process.

**Note:** the jsx template file(s), correspond to the
 [reactjs](https://facebook.github.io/react/) implementation.

**Note:** [babel](https://babeljs.io/) converts [ES6](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf),
 and [jsx](https://facebook.github.io/react/docs/jsx-in-depth.html) to
 [ES5](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf),
 which runs in the browser. [browserify](http://browserify.org/), helps bundle
 files containing "require(...)" statements into a single file.