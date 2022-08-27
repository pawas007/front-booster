# Pawo Fast Front using Sass and Gulp 4

Using a set of Pawo Fast Front Booster files when you're starting a website project can be a huge time-saver. Instead of having to start from scratch or copy and paste from previous projects, you can get up and running in just a minute or two.

I wanted to share my own Buster that I use for simple front-end websites that use HTML, SCSS, and JavaScript. And I'm using Gulp 4 to compile, prefix, and minify my files.

I also wrote a rather detailed walkthrough on how to get up and running with Gulp 4, as well as migration tips from Gulp 3. 

## Quickstart guide

* Clone or download this Git repo onto your computer.
* Install [Node.js](https://nodejs.org/en/) if you don't have it yet.
* Run `npm install`
* Run `gulp` to run the default Gulp task

In this proejct, Gulp is configured to run the following functions:

* Compile the SCSS files to CSS
* Autoprefix and minify the CSS file
* Concatenate the JS files
* Uglify the JS files
* Move final CSS and JS files to the `/dist` folder


* gulp - start gulp
* gulp watch - watch any changes and reload project
 
