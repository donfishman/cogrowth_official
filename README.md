# myproject

> firstproject

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).



����Ŀ��pc��vue��Ŀ������Ŀ��һ����������Ϊ�������⣬����IE10�ģ�Ҫ��û��IE10�����
���磺babel-polyfill.js:750 Uncaught Error: only one instance of babel-polyfill is allowed
		at Object.eval (webpack-internal:///./node_modules/babel-polyfill/lib/index.js:10)
		at eval (webpack-internal:///./node_modules/babel-polyfill/lib/index.js:29)
		at Object../node_modules/babel-polyfill/lib/index.js (babel-polyfill.js:750)
		at __webpack_require__ (babel-polyfill.js:679)
		at fn (babel-polyfill.js:89)
		at Object.0 (babel-polyfill.js:3346)
		at __webpack_require__ (babel-polyfill.js:679)
		at babel-polyfill.js:725
		at babel-polyfill.js:728
