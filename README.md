# Deep case utils

Set of case utils for JavaScript objects

Usage:

```js
	var deepCaseUtis = require('deep-case-utils');

	var object = { foo_bar: [{ bar_baz: 123 }, 345 ] };

	var camelCasedObject = deepCaseUtis.camelCase(object);
	//{ fooBar: [{ barBaz: 123 }, 345 ] }

```

List of available utils: 

	*  upperCase
	*  lowerCase
	*  snakeCase
	*  pascalCase
	*  camelCase
	*  kebabCase
	*  constantCase
	*  capitalCase
	*  titleCase
	*  flipCase

For more info see https://github.com/nbubna/Case