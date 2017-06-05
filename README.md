## SCSS Starter

A basic application for compiling SCSS to CSS.

## Configuration

Start by cloning the repository:

```
$ git clone https://github.com/alissalikavec/grunt-scss.git
```

First, this project uses Node and NPM - read and follow [Bloc's resource on installing Node and NPM](https://www.bloc.io/resources/npm-and-package-json#install-node-and-npm) before getting started. You'll need to install them before moving on.

The project uses [Grunt](https://gruntjs.com/) to run tasks in development, specifically to compile our `main.scss` file to `main.css`. You can review Bloc's [resource on using Grunt](https://www.bloc.io/resources/using-grunt) before using this application if you're curious.

Once you've installed Node and NPM, install the project dependencies by running this command inside of your project's directory:

```
$ npm install
```

Do this before doing anything else.


## Run the Application

Once you've run `npm install`, compile the SCSS stylesheet to CSS by entering this into your terminal:

```
$ grunt
```

This will compile your `main.scss` file into `main.css`.

You'll be writing your styles in `main.scss`, and when you run `grunt` in your terminal those styles will be compiled into `main.css`. *Don't write your CSS in `main.css` or it will be overwritten!*

`main.css` is loaded via `index.html`, which then displays our styles. Yay!

## Sass/SCSS Documentation
SCSS is the main syntax for Sass. [Check out what you can do with it in the docs.](http://sass-lang.com/guide)
