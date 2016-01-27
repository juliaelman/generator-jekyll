# Generator jekyll
[![Build Status](https://secure.travis-ci.org/thomas-lebeau/generator-jekyll.png?branch=master)](https://travis-ci.org/thomas-lebeau/generator-jekyll)

A generator for Yeoman to bootstrap a Jekyll blog.

## Dependencies
- [yo](https://github.com/yeoman/yo) `npm install -g yo`
- [Jekyll](http://jekyllrb.com/) `gem install jekyll`

## Getting started
- Install the generator: `npm install [-g] generator-jekyll`
- Run: `yo jekyll`to scaffold your project
- Run `grunt` for building and `grunt server` for preview

## Options

- `--skip-install`

  Skips the automatic execution of `bower` and `npm` after
  scaffolding has finished.

- `--test-framework=[framework]`

  Defaults to `mocha`. Can be switched for
  another supported testing framework like `jasmine`.

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)

## Author
*Thomas Lebeau*

- [http://lebeau.io](http://lebeau.io)
- [@tomalebeau](http://twitter.com/tomalebeau)
