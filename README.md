# Carolgonzalez

## Description

Carolgonzalez is a Node.js module that provides a collection of utility functions for common tasks.

## Installation

You can install this module via npm: `npm install carolgonzalez`

## Usage
```javascript
const { getRandomInt, delay, fetchRandomDogImage, capitalizeFirstLetter } = require('fluentutils');

console.log(getRandomInt(1, 10)); // Output: A random integer between 1 and 10
delay(2000).then(() => console.log('Delayed execution')); // Output: After 2 seconds, 'Delayed execution' will be printed
fetchRandomDogImage().then(imageUrl => console.log(imageUrl)); // Output: URL of a random dog image
console.log(capitalizeFirstLetter('hello')); // Output: 'Hello'
```
