# news
Npm Module that returns latest 10 News
[![npm (scoped)](https://img.shields.io/badge/NPM-V%201.1.1-blue)](https://www.npmjs.com/package/techtwiddle-news-list)

## Install

```
$ npm i techtwiddle-news-list
```

## Usage

```js
const news = require("techtwiddle-news-list"); 

news()
  .then((res) => {
    
    console.log(res.data); // Print the news data on the console
  })
  .catch((err) => {
    console.log(err); // Error handler
  });
```

## How to run
```
node index.js
```
