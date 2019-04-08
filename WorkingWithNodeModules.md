Questions

1. How do you import a module?

To import a module you use `require`. For example, to import the `fs` library you would write the following code:
`const fs = require('fs');`

2. What JavaScript statement do you use to export a module?

To export a module you use `export`. For example:
```
module.exports.ls = () => {
  };
```

Online Research Questions

1. Are there other ways to export a module?

Yes, in this checkpoint we went over exporting as a function but it can also be as simple as a string.
`module.exports = 'Hello world';`
You can also attach properties or methods to the `export` object:
`module.exports.Message = 'Hello world';`
You can also attach objects or classes to the `export` object. The syntax for exports can be written as `module.exports` or simply as `exports`.

2. What are ES6 modules and how do they differ from the module we created in this checkpoint?

ES6 libraries are very similar to the Node module we created in this checkpoint in that they are both reusable pieces of code that provide some sort of functionality.
The main difference between the two is that an ES6 library provides a functionality for a webpage, such as making a slideshow, whereas a Node module is for the backend. To use an ES6 library you use the `script` tag with a `src` reference to the location of the library. To use a Node module you use `require`.
