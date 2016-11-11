# interface-design-template

A starter project including full setup for Handlebars, GulpJS, SASS, BrowserSync, bourbon, latest foundation and bootstrap.

**Please open all issue with this template on the main [Interface Design for Websites](https://github.com/bhanubais/interface-design-template/issues) repo.**

This is the official BHANUBAIS Template for use with [Foundation for Sites](http://foundation.zurb.com/sites), [Bootstrap](https://v4-alpha.getbootstrap.com/), [Bourbon - A Lightweight Sass Tool Set](http://bourbon.io/docs/). I use this template to deliver static code to our clients. It has Gulp-powered build system with theme features:

- Zurb Foundation
- Bootstrap
- Bourbon
- Handlebars HTML templates with Panini
- SASS compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production build:
	- CSS compression
	- JavaScript compression
	- Image compression

## Pre-Requirements

To use this template, your computer needs following requirements

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

## Installation

To setup the template, first download it with Git:

```bash
git clone https://github.com/bhanubais/interface-design-template projectname
```

Then open the folder in your command line, and install the needed dependencies:
(This template featured with browser-sync so npm command will takes more time than usuall on windows based PCs)

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:3007
```

To create compressed, production-ready assets, run `npm run build`.
