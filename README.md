# nano-shuffle

Micro shuffle array function, tiny implementation of [Durstenfeld shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle#The_modern_algorithm). Copy-pasta from https://stackoverflow.com/a/12646864/978690.

## Install

```
npm install nano-shuffle
```

## Use

```javascript
import shuffle from 'nano-shuffle';

const list = [1, 2, 3];
shuffle(list);
```
