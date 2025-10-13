<h1 align="center">isFalse</h1>
<p align="center"><em>Checks if a boolean is true or false</em></p>

## Why use this package?
This is the most elegant and simplest way of figuring out if a boolean is false, without using complicated `if` statements!

## Features
* Check if a boolean is true or false
* yeah that's pretty much it...

## How to install?
Using your favorite node package manager, some examples below:
```sh
bun install -g @smilt/isfalse
pnpm add -g @smilt/isfalse
npm add -g @smilt/isfalse
```

## Example Usage (Typescript)
```js
import isFalse from '@smilt/isfalse'

const variable1 = false
const variable2 = true

console.log(isFalse(variable1)) // Returns: true
console.log(isFalse(variable2)) // Returns: false
```

## License
[MIT License](LICENSE)
