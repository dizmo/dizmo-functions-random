[![Build Status](https://travis-ci.org/dizmo/dizmo-function-random.svg?branch=master)](https://travis-ci.org/dizmo/dizmo-function-random)
[![Coverage Status](https://coveralls.io/repos/github/dizmo/dizmo-function-random/badge.svg?branch=master)](https://coveralls.io/github/dizmo/dizmo-function-random?branch=master)

# @dizmo/random
Attaches to the `String` type a `random` function which returns a random string for the provided length and range, where the length needs to be in `[0..8]` and the range in `[2..36]`. By default the length is `0`, and hence any empty string is the result.

**NOTE**: The implementation of this functions is *not* cryptographically secure, and hence it should *only* be used in non-security related use cases! Internally it is based on the `Math.random` function.

## Usage
### Install
```sh
npm install @dizmo/random --save
```
### Require
```javascript
require('@dizmo/random');
```
### Examples
```javascript
String.random(8);
```
```javascript
us7c55xs
```
```javascript
String.random(8, 2);
```
```javascript
11001000
```
## Development
### Build
```sh
npm run build
```
### Lint
```sh
npm run lint
```
#### with fixes:
```sh
npm run lint:fix
```
### Test
```sh
npm run test
```
### Cover
```sh
npm run cover
```

## Copyright

 © 2018 [dizmo AG](http://dizmo.com/), Switzerland
