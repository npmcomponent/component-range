*This repository is a mirror of the [component](http://component.io) module [component/range](http://github.com/component/range). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-range`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# range

  Return a range of integers

## Installation

    $ component install component/range

## API

  Exclusive range:

```js
range(5, 10);
// => [5,6,7,8,9]
```

  Inclusive range (truthy value):

```js
range(5, 10, true);
range(5, 10, 'inclusive');
// => [5,6,7,8,9,10]
```

## License

  MIT
