# grunt-docco-husky

Grunt Docco-husky plugin.

## Getting Started
Install this grunt plugin next to your project's [grunt.js gruntfile][getting_started] with: `npm install grunt-docco-husky`

Then add this line to your project's `grunt.js` gruntfile:

```javascript
grunt.loadNpmTasks('grunt-docco-husky');
```
You can add parameters to the grunt docco husky task and hook it to your development workflow like so:

```javascript
grunt.initConfig({
  docco_husky : {
    args:['-name', 'test', 'js/*.js', 'assets/js/modules/*.js']
  },
  watch : {
    files: ['js/*.js', 'spec/javascripts/libs/*.spec.js'],
    tasks: 'docco_husky'
  }
});
```

[grunt]: https://github.com/cowboy/grunt
[getting_started]: https://github.com/cowboy/grunt/blob/master/docs/getting_started.md

## Documentation
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [grunt][grunt].

## Release History
_(Nothing yet)_

## License
Copyright (c) 2012 David Souther  
Licensed under the MIT license.
