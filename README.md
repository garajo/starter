# Starter

Start project for frontend applications using:

- **[Browserify][browserify]** - Allows `require('module')` style imports in your frontend JavaScript code.
- **[Gulp][gulp]** - A lightning fast task runner.
- **[Mithril][mithril]** - A light weight JavaScript MVC framework with virtual DOM diffing, auto-redraw and amazingly fast execution speeds all with a very short learning curve.
- **[LESS][less]** - A CSS preprocessor with variables, functions, and tons of utilities to make writing CSS suck less.
- **[fb-flo][flo]** for automatic reloading of your HTML, CSS and JavaScript code without refresh.

Running the gulp scripts (see below), allows you to do some other awesome things like:

- Generate sourcemaps for you CSS and JavaScript
- Automatically concatenate and minify your CSS and JavaScript
- Run code linting on your JavaScript
- Automatically run your test suite on any changes (with an awesome test runner to boot!).


## Usage

To get started, make sure you have [Node.js][node] installed and then run:

```bash
npm install -g gulp
```

[Gulp][gulp] is a task runner, similar to Grunt but with a more code driven approach to defining tasks. See the `gulpfile.js` for all the available tasks.

For local development, you'll most likely want to run the `watch` task:

```bash
gulp watch
```

This will startup a webserver using [fb-flo][fb-flo], watch for changes to your JavaScript, HTML and LESS files and automatically rebuild them. It will open up the application in your default browser when you first run it to streamline the development process.

Try running `gulp watch` in one tab in your terminal program and then edit a LESS, HTML or JavaScript file and watch the page reload automatically. Sexy.

**Note:** You'll need to install the [fb-flo browser extension][fb-flo-extension] for fb-flo to work.


## Credits

Built by [Dana Woodman][dana], founder of [BIG][big].

Credit also goes to the authors of all the amazing tools used in this project. Without people like them, we'd still be in the dark ages of technology.


## License

This source code is released under a liberal [MIT license][mit] (which means you can use it in commercial projects). See the `LICENSE` file for details.

[mithril]: http://lhorie.github.io/mithril/index.html
[browserify]: http://browserify.org/
[dana]: http://danawoodman.com/
[big]: http://builtbybig.com/
[mit]: http://opensource.org/licenses/MIT
[less]: http://lesscss.org/
[node]: http://nodejs.org/
[gulp]: http://gulpjs.com
[fb-flo]: https://github.com/facebook/fb-flo
[fb-flo-extension]: https://chrome.google.com/webstore/detail/ahkfhobdidabddlalamkkiafpipdfchp
