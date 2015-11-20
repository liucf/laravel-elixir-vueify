# Usage

## Step 1: Install

```
npm install laravel-elixir-vueify
```

## Step 2: Require

Within your main `Gulpfile`, add:

```js
var elixir = require('laravel-elixir');

require('laravel-elixir-vueify');

elixir(function(mix) {
    mix.browserify('main.js');
});
```

Notice above, where we require `laravel-elixir-vueify`. That's all you need. Behind the scenes, all of the necessary dependencies have been installed, and Vueify has been inserted into Laravel Elixir's Browserify transformers list.

## Step 3. Build Amazing Things

You're done. :)