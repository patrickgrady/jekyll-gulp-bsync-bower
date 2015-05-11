# jekyll-gulp-bsync-bower
A project starter kit for a Jekyll site using Gulp, Node-Sass, BrowserSync, and Bower to manage Sass plugins.

Streamline your workflow with super-fast compiling, Sass in the web inspector, minified + autoprefixed CSS output, and live auto-updating everything across multiple devices — all from a single terminal command!

The following packages and plugins make it happen:
* [Jekyll](http://jekyllrb.com/): A static site generator and blogging platform with github-pages integration.
* [Node-Sass](https://github.com/sass/node-sass): Blazing-fast, agnostic Sass!
* [BrowserSync](http://www.browsersync.io/): For auto-updating multi-device magic.
* [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md): A super flexible and customizable taskrunner.
* [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer): Auto-prefixes CSS so you don't have to.
* [gulp-rename](https://www.npmjs.com/package/gulp-rename): Pretty self-explanatory.
* [gulp-sass](https://www.npmjs.com/package/gulp-sass): So Gulp can swallow Node-flavored Sass.
* [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps): Inspect Element: See Sass.
* [Bower](http://bower.io/): A handy node-based package manager.
* [Modular Scale](https://github.com/modularscale/modularscale-sass): An awesome math-based approach for creating typographic harmony.
* [Breakpoint-Sass](https://github.com/at-import/breakpoint): The best breakpoints in the biz.
* [Susy](https://github.com/ericam/susy/): An unopinionated grid utility.

##To Get Started
First, if you haven't done so already, install [Node JS](https://nodejs.org/) and [NPM](http://blog.npmjs.org/post/85484771375/how-to-install-npm). Homebrew makes this very easy, just type the following commands and you'll be good to go.
~~~
brew update
brew doctor
brew install node
~~~

Next, clone the starter kit repository:
~~~
git clone git@github.com:patrickgrady/jekyll-gulp-bsync-bower.git
~~~

Then navigate to the project folder:
~~~
cd into/the/repository
~~~

Now install the required packages:
~~~
npm install
bower install
~~~

####Sweet, Sweet Automation...
A single word on the command line starts the build system and watches for changes.
~~~
gulp
~~~

Note: If you're having trouble you may need to install these packages globally.
~~~
npm install gulp -g
npm install browser-sync -g
npm install bower -g
~~~
