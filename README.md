[travis-url]: https://travis-ci.org/groupe-sii/compodoc
[travis-image]: https://travis-ci.org/groupe-sii/compodoc.svg?branch=develop
[npm-url]: https://badge.fury.io/js/compodoc
[npm-image]: https://badge.fury.io/js/compodoc.svg

<p align="center">
  <img src="https://avatars3.githubusercontent.com/u/23202313" alt="Compodoc: The missing documentation tool for your Angular 2 application" width="226">
  <br>
  [![npm version][npm-image]][npm-url]
  [![Build Status][travis-image]][travis-url]
</p>

<p align="center">The missing documentation tool for your Angular 2 application.</p>

Features
------------

* **Clean, simple design** — With Compodoc, the main endpoints are on the left side of your documentation, and all the content on the right side. Compodoc is responsive, so it looks great on tablets, phones, and even in print.

* **Compodoc is just markdown** — Write your comments With Markdown, provide externals Markdown files for enhancing the API documentation.

* **Automatic table of contents** - API table of contents is generated using elements found during files parsing

## Demo using [SoundCloud API client with Angular2 project](https://github.com/r-park/soundcloud-ngrx)

README page             |  Overview page
:-------------------------:|:-------------------------:
![screenshot-1](https://raw.githubusercontent.com/groupe-sii/compodoc/master/screenshots/1.png)  | ![screenshot-1](https://raw.githubusercontent.com/groupe-sii/compodoc/master/screenshots/2.png)
Modules page             |  Single module page
![screenshot-1](https://raw.githubusercontent.com/groupe-sii/compodoc/master/screenshots/3.png)  | ![screenshot-1](https://raw.githubusercontent.com/groupe-sii/compodoc/master/screenshots/4.png)

Getting Started with compodoc
------------------------------

## Install

Install from npm: `npm install -g compodoc`

## Usage

```
$ compodoc --help

Usage: compodoc [options]

Options:

  -h, --help               output usage information
  -V, --version            output the version number
  -f, --file [file]        A tsconfig.json file
  -o, --open               Open the generated documentation
  -s, --serve              Serve generated documentation
  -g, --hideGenerator      Do not print the Compodoc link at the bottom of the page
  -d, --output [folder]    Where to store the generated documentation
```

## Why this tool ?

Because we doesn't find our needs on existing tools. We want to have a single place where there is :
- api documentation of code (typedoc)
- component(s) documentation
- general documentation (\*.md files)

## Why not a SPA for outputed documentation ?

[KISS principle](https://en.wikipedia.org/wiki/KISS_principle) or shortly __"Keep it simple"__. We think static html files are simpler than another SPA inside an "SPA documentation".

## Roadmap

- [ ] module(s) page(s) with ngmodule comments
- [x] module(s) page(s) started
- [ ] component(s) page(s) with @component comments, API, class
- [x] component(s) page(s) started
- [ ] handle external markdown files as "functional" documentation
- [ ] routes
- [ ] directives
- [ ] injectables
- [ ] classes
- [ ] pipes
- [ ] support for Angular 1.5+ projects written in Typescript

## Resources

Inspired by stuff from [angular2-dependencies-graph](https://github.com/manekinekko/angular2-dependencies-graph)

## License

The MIT License (MIT)
Copyright (c) 2016

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
