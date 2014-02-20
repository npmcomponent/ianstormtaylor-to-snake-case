*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-snake-case](http://github.com/ianstormtaylor/to-snake-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-snake-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-snake-case

  Convert a string to a snake case.

## Installation

    $ component install ianstormtaylor/to-snake-case
    $ npm install to-snake-case

## Example

```js
var snake = require('to-snake-case');

snake('camelCase');  // "camel_case"
snake('space case'); // "snake_case"
snake('dot.case');   // "dot_case"
snake('weird[case'); // "weird_case"
```

## API

### toSnakeCase(string)
  
  Returns the snake-case variant of a `string`.

## License

  MIT
