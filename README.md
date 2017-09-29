# laravel-mix-html-pug
Make html page use laravel-mix and pugjs
## Install

``` bash
$ npm install --save-dev laravel-mix-html-pug
```

``` js
// webpack.mix.js

let mix = require('laravel-mix');

mix.setPublicPath('dist');
mix.pug = require('laravel-mix-html-pug');

/**
 * HTML Views
 */
mix.html('src/views', 'public/views');

// ...
```

## Official Documentations

- Documentation for Pug can be found on the [Pug website](http://pugjs.org).
- Documentation for Mix repositories can be found on the [Github](https://github.com/JeffreyWay/laravel-mix)


## Thanks

- [laravel-mix-pug](https://github.com/matejsvajger/laravel-mix-pug) - API for this src/tasks module
- [laravel-blade-jade](https://github.com/iguntur/laravel-blade-jade) - API for this README.md

## License

MIT @ [JMJ](https://escapeplan.me)