![build](https://github.com/iamsaifraihan/utilitykit-js/workflows/build/badge.svg)
[![Coverage Status](https://coveralls.io/repos/github/iamsaifraihan/utilitykit-js/badge.svg?branch=master)](https://coveralls.io/github/iamsaifraihan/utilitykit-js?branch=master)
[![License](https://img.shields.io/github/license/iamsaifraihan/utilitykit-js?color=blue)](https://github.com/iamsaifraihan/utilitykit-js/blob/master/LICENSE)

# utilitykit-js

This repository offers a set of versatile, standalone JavaScript utility functions created for diverse project needs. Rather than a monolithic library, it focuses on providing individual, easily modifiable functions that developers can adapt to their specific requirements. The utilities are grouped into functional packages, including utilities for arrays, strings, objects, and functions.

## Table of Contents

### Array

- **[chunk](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/chunk)**: Creates an array of elements split into groups the length of size specified.
- **[compact](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/compact)**: Creates an array with all falsy values removed. 'false', 'null', '0', '""', 'undefined', and 'NaN' are falsy.
- **[diff](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/diff)**: Returns an array with only the unique values from the first array, by excluding all values from the second array using strict equality for comparisons.
- **[drop](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/drop)**: Creates a slice of `array` with `n` elements dropped from the beginning.
- **[dropRight](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/dropRight)**: Creates a slice of `array` with `n` elements dropped from the end.
- **[dropRightWhile](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/dropRightWhile)**: Creates a slice of `array` excluding elements dropped from the end, until `predicate` returns falsy.
- **[dropWhile](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/dropWhile)**: Creates a slice of `array` excluding elements dropped from the beginning, until `predicate` returns falsy.
- **[groupBy](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/groupBy)**: Creates an object composed of keys generated from the results of running each element of `array` through `iteratee`.
- **[intersect](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/intersect)**: Creates an array of unique values that are included in all given arrays.
- **[insert](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/insert)**: Inserts one or more elements to array at a specific index.
- **[move](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/move)**: Moves an array element to a different position.
- **[partition](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/partition)**: Creates an array of elements split into two groups (arrays) depending on the result of a predicate function invoked for each iteration.
- **[pluck](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/pluck)**: Retrieves the value of a specified property from all elements in an array.
- **[remove](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/remove)**: Removes one or more elements from an array at the specified index(es).
- **[shuffle](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/shuffle)**: Returns a new array with its elements' order randomized, using the Fisher-Yates (aka Knuth) Shuffle algorithm.
- **[tail](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/tail)**: Gets all but the first element of array.
- **[take](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/take)**: Creates a slice of array with `n` items taken from the beginning.
- **[takeRight](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/takeRight)**: Creates a slice of array with `n` items taken from the end.
- **[takeRightWhile](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/takeRightWhile)**: Creates a slice of `array` with elements taken from the end, until `predicate` returns falsy.
- **[takeWhile](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/takeWhile)**: Creates a slice of `array` with elements taken from the beginning, until `predicate` returns falsy.
- **[sort](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/sort)**: Sorts an **array of primitive values**.
- **[sortBy](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/sortBy)**: Sorts an **array of objects** by a property.
- **[uniq](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/uniq)**: Creates a duplicate-free version of an array, using SameValueZero for equality comparisons.
- **[uniqBy](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/uniqBy)**: Creates a duplicate-free array by accepting an `iteratee` which is invoked for each element in array.
- **[zip](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/arrays/zip)**: Creates an array of grouped elements, the first of which contains the first elements of the given arrays, the second of which contains the second elements of the given arrays, and so on.

### String Utilities

- [camelCase](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/camelCase): Converts a string to [camel case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles), e.g., `'theQuickBrownFoxJumpsOverTheLazyDog'`.
- [capitalize](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/capitalize): Capitalizes the first character of a string (optionally converts the rest of the string to lowercase).
- [classnames](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/classnames): Creates a string by conditionally joining class names together.
- [collapseWhitespace](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/collapseWhitespace): Converts all adjacent whitespace characters to a single space.
- [deburr](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/deburr): Deburrs a string by converting Latin-1 supplementary letters to basic Latin letters and removing combining diacritical marks.
- [escapeHTML](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/escapeHTML): Converts the characters `&`, `<`, `>`, `"`, and `'` in a string to their corresponding HTML entities.
- [escapeRegExp](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/escapeRegExp): Escapes `RegExp` special characters in a string.
- [kebabCase](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/kebabCase): Converts a string to [kebab case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles), e.g., `'the-quick-brown-fox-jumps-over-the-lazy-dog'`.
- [lines](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/lines): Returns an array with the lines of a string.
- [numberFormat](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/numberFormat): Formats a number based on the number of decimal points, the decimal separator, and the thousands separator.
- [pascalCase](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/pascalCase): Converts a string to [pascal case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles), e.g., `'TheQuickBrownFoxJumpsOverTheLazyDog'`.
- [randomString](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/randomString): Generates a pseudo-random string of specific `length`, allowing a set of characters specified by `chars`.
- [removePrefix](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/removePrefix): Removes a substring (prefix) from the start of a string.
- [removeSuffix](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/removeSuffix): Removes a substring (suffix) from the end of a string.
- [snakeCase](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/snakeCase): Converts a string to [snake case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles), e.g., `'the_quick_brown_fox_jumps_over_the_lazy_dog'`.
- [squash](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/squash): Removes all spaces from a string; optionally removes any escape sequences such as `\t`, `\n`, `\f`, `\r`, and `\v`.
- [strip](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/strip): Returns a new string with all occurrences of arguments passed removed.
- [stripHTML](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/stripHTML): Returns a new string with all HTML tags removed.
- [stripPunctuation](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/stripPunctuation): Returns a new string with all punctuation removed.
- [substringAfter](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/substringAfter): Returns a substring after a specific sequence of character(s).
- [substringBefore](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/substringBefore): Returns a substring before a specific sequence of character(s).
- [supplant](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/supplant): Performs variable substitution in a string.
- [truncate](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/truncate): Truncates a string based on character count.
- [unescapeHTML](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/unescapeHTML): Converts the HTML entities `&amp;`, `&lt;`, `&gt;`, `&quot;`, `&#34;`, and `&#39;` in a string to their corresponding characters.
- [words](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/strings/words): Splits a string into an array of its words.

## Object

- **[get](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/objects/get)**: Gets the `value` at path of `object`. If the resolved value is `undefined`, the `defaultValue` is returned in its place.
- **[omit](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/objects/omit)**: Creates an object composed of the own enumerable (not inherited) property paths of object that are not omitted.
- **[pick](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/objects/pick)**: Creates an object composed of the picked object properties.
- **[pickBy](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/objects/pickBy)**: Creates an object composed of the object enumerable properties that predicate returns truthy for.
- **[trueTypeOf](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/objects/trueTypeOf)**: Determines the true type of a value using `Object.prototype.toString.call()`.

## Function

- **[after](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/after)**: Creates a function that invokes `fn` once it's called `n` or more times.
- **[ary](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/ary)**: Creates a function that accepts up to `n` arguments, ignoring any additional arguments.
- **[before](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/before)**: Creates a function that invokes `fn` while it’s called less than `n` times.
- **[compose](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/compose)**: Performs right-to-left function composition.
- **[curry](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/curry)**: Returns a curried equivalent of the provided function.
- **[debounce](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/debounce)**: Returns a function, that, as long as it continues to be invoked, will not be triggered. The function will be called after it stops being called for 'n' milliseconds.
- **[flip](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/flip)**: Creates a function that invokes the original function with its parameters reversed.
- **[negate](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/negate)**: Creates a function that negates the result of the predicate `fn`.
- **[once](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/once)**: Ensure a given functionality only runs once.
- **[partial](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/partial)**: Creates a new function that invokes the provided function with partials prepended to the arguments it receives.
- **[partialRight](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/partialRight)**: Creates a new function that invokes the provided function with partials appended to the arguments it receives.
- **[pipe](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/pipe)**: Performs left-to-right function composition.
- **[throttle](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/throttle)**: Limits the number of times a function can be called in a given period.
- **[unary](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/function/unary)**: Creates a function that accepts up to one argument, ignoring any additional arguments.

## Is

- **[isArray](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isArray)**: Checks if a value is an array.
- **[isArrayLike](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isArrayLike)**: Checks if a value is array-like.
- **[isArrayLikeObject](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isArrayLikeObject)**: Checks if a value is array-like and object as well.
- **[isBoolean](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isBoolean)**: Checks if a value is boolean.
- **[isDate](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isDate)**: Checks if a value is a date object.
- **[isElement](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isElement)**: Checks if a value is a DOM element.
- **[isEmail](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isEmail)**: Validates a string as email address.
- **[isEmpty](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isEmpty)**: Checks if a value is an empty object, collection, map, or set.
- **[isEven](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isEven)**: Checks if a value is even.
- **[isFalse](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isFalse)**: Checks if a value is `false` (strict equality).
- **[isFalsy](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isFalsy)**: Checks if a value is falsy.
- **[isFiniteNum](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isFiniteNum)**: Checks if a value is a finite number.
- **[isFlatArray](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isFlatArray)**: Checks if a value is a flat array.
- **[isFunction](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isFunction)**: Checks if a value is a function.
- **[isHexadecimal](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isHexadecimal)**: Checks if a value matches a hexadecimal regular expression.
- **[isHexColor](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isHexColor)**: Checks if a value matches a hexadecimal color regular expression.
- **[isInteger](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isInteger)**: Checks if a value is an integer number.
- **[isIterable](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isIterable)**: Checks if a value is an iterable.
- **[isMap](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isMap)**: Checks if a value is classified as a Map object.
- **[isNaN](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isNaN)**: Determines whether the passed value is `NaN` and its type is `Number`.
- **[isNull](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isNull)**: Checks if a value is `null`.
- **[isNullish](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isNullish)**: Checks if a value is `null` or `undefined`.
- **[isNumber](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/is/isNumber)**: Checks if a value is a number.
- \*\*[isObject](https://github.com/iamsaifraihan/utilitykit-js/tree/

### Math

|### Math

- **[average](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/average)**: Calculates the average of a set of numbers.
- **[clamp](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/clamp)**: Clamps number within the inclusive lower and upper bounds.
- **[degreesToRadians](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/degreesToRadians)**: Converts degrees to radians.
- **[inRange](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/inRange)**: Checks if a number is between `min` and `max` including.
- **[lerp](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/lerp)**: Takes a normalized value within a range of values and converts it to a numerical value that the normalized value points to.
- **[normalize](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/normalize)**: Takes a value within a range of values and converts that value to a number from 0 to 1 that indicates where it lies in that range.
- **[max](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/max)**: Returns the largest of zero or more numbers.
- **[min](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/min)**: Returns the smallest of zero or more numbers.
- **[radiansToDegrees](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/radiansToDegrees)**: Converts radians to degrees.
- **[randomDist](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/randomDist)**: Returns a weighted random number (that tends to the center) of a range of numbers based on the number of the iterations set.
- **[randomInt](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/randomInt)**: Returns a pseudo-random integer number between a min (inclusive) and a max (inclusive) value.
- **[randomRange](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/randomRange)**: Returns a pseudo-random number between a min (inclusive) and a max (exclusive) value.
- **[roundToNearest](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/roundToNearest)**: Rounds a number to the nearest multiple of a value provided.
- **[roundToPlaces](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/math/roundToPlaces)**: Rounds a number to a number of desired places.

### DOM

- **[convertImageToBase64](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/convertImageToBase64)**: Converts an image's content to Data URI scheme.
- **[cookie](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/cookie)**: Create, read and delete cookies.
- **[highResolutionCanvas](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/highResolutionCanvas)**: Processes an `HTMLCanvasElement` by downsampling on the canvas to ensure that the drawn visuals do not look blurry on high-DPI screens.
- **[mediaQuery](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/mediaQuery)**: Determines if the document matches a media query string.
- **[preloadImages](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/preloadImages)**: Asynchronously load images to browser so that can be cached.
- **[whichAnimationEnd](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/whichAnimationEnd)**: Detects the supported property name for the "animationend" event.
- **[whichTransitionEnd](https://github.com/iamsaifraihan/utilitykit-js/tree/master/packages/dom/whichTransitionEnd)**: Detects the supported property name for the "transitionend" event.

## Development

### Installation

#### Clone repo

```sh
git clone https://github.com/iamsaifraihan/utilitykit-js.git
```

#### Install dev dependencies

```sh
npm install
```

### Test

```sh
npm test
npm run test:watch # Run tests in watch mode
```

### Generate documentation

Generates markdown documentation for a single file and prints it to stdout.

```sh
npm run docs <path-to-file>
```

## License

[The MIT License (MIT)](https://github.com/iamsaifraihan/utilitykit-js/blob/master/LICENSE)
