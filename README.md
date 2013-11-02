node-city-reverse-geocoder
==========================

A simple, fast, database-less reverse geocoder for Node.js

Install
-------

    npm install city-reverse-geocoder

Usage
-----

An example of using the tree:
```javascript
var crg = require('city-reverse-geocoder');

// Return the nearest city to (48.8567, 2.3508) in kilometers
console.log(crg(48.8567, 2.3508));

// Return the nearest city to (48.8567, 2.3508) in miles
console.log(crg(48.8567, 2.3508, 1, 'mi'));

// Return the top 3 nearest cities to (48.8567, 2.3508) in kilometers
console.log(crg(48.8567, 2.3508, 3 /*, 'km' (default) */));

// Return the top 3 nearest cities to (48.8567, 2.3508) in miles
console.log(crg(48.8567, 2.3508, 3, 'mi'));
```

