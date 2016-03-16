# CSS Typography utilities

## Installation

* [npm](http://npmjs.org/): `npm install @precisionnutrition/utils-typography`
* Download: [zip](https://github.com/precisionnutrition/utils-typography/releases/latest)

## Available classes

* `u-bold` - Set text to bold.
* `u-semiBold` - Set text to semi-bold.
* `u-regular` - Set text to regular.
* `u-italic` - Set text to italic.
* `u-caps` - Use all capital letters.
* `u-capitalize` - Capitalize words.
* `u-underline` - Adds an underline decoration.
* `u-noDecoration` - Remove text decoration.
* `u-textKern` - Enable kerning in supported browsers.
* `u-nowrap` - Prevent wrapping at whitespace.
* `u-breakWord` - Break strings when their length exceeds the width of their container.
* `u-lineHeight1` - Set line-height to value 1.
* `u-lineHeight2` - Set line-height to value 2.
* `u-lineHeight3` - Set line-height to value 3.
* `u-lineHeight4` - Set line-height to value 4.
* `u-leftAlign` - Left-align text.
* `u-centerAlign` - Centre-align text.
* `u-rightAlign` - Right-align text.
* `u-justify` - Justify text.
* `u-truncate` - Cut off text after one line with an ellipsis.

## Usage

Please refer to the README for [SUIT CSS utils](https://github.com/suitcss/utils/)

## Testing

Install [Node](http://nodejs.org) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](http://stylelint.io/)

```
npm run lint
```

To generate the testing build.

```
npm run build-test
```

To watch the files for making changes to test:

```
npm run watch
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox (latest)
* Safari 5+
* Internet Explorer 9+
