# \{{moment}}

> This is a forked version of https://www.npmjs.com/package/handlebars-helper-moment the only difference being the moment.js file in root. Combining the powers of Assemble, Handlebars.js and Moment.js. This helper leverages Moment.js to provide ultimate control over manipulating time and dates in your templates.

## Quickstart
Install the helper:

```bash
npm i helper-moment-handlebars --save-dev
```

Now add the helper to Assemble's options:

```js
assemble: {
  options: {
    // Assemble will automatically resolve the path
    helpers: ['helper-moment-handlebars', 'foo/*.js']
  }
}
```


## Original Author

**Mikko Tapionlinna**

+ [github.com/Arkkimaagi](https://github.com/Arkkimaagi)

## License
Copyright (c) 2014 Mikko Tapionlinna, contributors.
Released under the MIT license

***

[moment]: http://momentjs.com/docs/ "Moment.js"
[grunt]: http://gruntjs.com "Grunt.js"
