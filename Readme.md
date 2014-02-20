*This repository is a mirror of the [component](http://component.io) module [yields/empty](http://github.com/yields/empty). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-empty`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# empty

  empty an element.

## Installation

    $ component install yields/empty

## Example

```js
var el = document.createElement('div');
el.appendChild(document.createElement('ul'));
assert('' == empty(el).innerHTML);
```

## License

  MIT
