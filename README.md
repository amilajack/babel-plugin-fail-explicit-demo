babel-plugin-fail-explicit demo
===============================
**A simple demo of babel-plugin-fail-explicit**

```js
// index.js
const foo = 1
const bar = []

foo + bar
// ^ TypeError: Unexpected coercion of type "number" and type "array" using "+" operator
```


## Setup
```bash
git clone https://github.com/amilajack/babel-plugin-fail-explicit-demo.git
cd babel-plugin-fail-explicit-demo
npm i -g babel-cli
babel-node index.js
```
