# Create HTML templates based on Jekyll

jekyll-html-templates is a starter kit for creating front-end templates by using [Jekyll](https://jekyllrb.com/) as a static site generator.

- It follows an [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/) approach.
- It uses Jekyll’s include functionality together with the [Liquid templating language](https://jekyllrb.com/docs/templates/) to create small reusable components.
- It uses SASS for maintaining CSS.
- It has support for Browsersync.

## Requirements

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [RubyGems](https://rubygems.org/)
- [NodeJS](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

## Installation

Start by installing Jekyll. If you have RubyGems installed, it should be as simple as:

```sh
$ gem install jekyll
```

Then install the development dependencies with:

```sh
$ npm install
```

Finally install all 3rd party libraries with Bower:
```sh
$ bower install
```

## Usage

Run with:

```sh
$ gulp
```

That will start a server with Browsersync running. Every time a .html or .md file is saved it will rebuild Jekyll and output the new content automatically. Same thing with .scss and .js files.
