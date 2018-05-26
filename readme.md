<a href="https://lisi.es">
<img src="https://i.imgur.com/dsaOh1x.png" alt=".Lisi CSS Framework" width=337 height=35>
</a>

<br>

## Introduction

**.Lisi** is a clean starting point CSS framework to build websites without annoying styles. It has been built in SASS.

Is a simple, powerful, free and open source. It's not about a UI framework.

Designed to carry out projects that come from designers, so we can give the look we want to the design without styles that bother.

You can find the documentation and the reference guide in https://lisi.es (Coming soon)


## Getting started

First, install **.Lisi** in your project using one of the following methods:

**Download zip.**

[Download the latest release](https://github.com/maarestudio/lisi/releases/latest)

**Clone the git repository.**

```
$ git clone https://github.com/maarestudio/lisi.git
```

**Install with npm.**

```
$ npm install lisi-css
```

**Install with Yarn.**

```
$ yarn add lisi-css
```

**Install with Bower.**

```
$ bower install lisi-css
```


## Usage

The main `css` files is located in the `dist/` folder. Include it on every `HTML` file of your project by adding the following tag:

```
<link rel="stylesheet" type="text/css" href="./path/to/lisi-css/dist/lisi.min.css">
```

Or you can use the hosted version on [jsDelivr](https://www.jsdelivr.com):

```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lisi-css/dist/lisi.min.css">
```

Guides and reference are published in [https://lisi.es/documentation](https://lisi.es/documentation) (Coming soon). Take a look and start creating your web page!


## Using the SASS file

You can use the SASS file located in the `sass/` folder.

```
@import "lisi-css/sass/lisi.scss"
```

Remember that you must have [nodejs](https://nodejs.org) installed to install [npm packages](https://npmjs.com).


## Developers

**Clone the repository.**

```
$ git clone https://github.com/maarestudio/lisi.git
```

**Install dependencies.**

Now, `cd` to the **lisi** repository and install all the develop dependencies using `npm` or `yarn`:

```
$ npm install
```
```
$ yarn install
```

**SASS watcher.**

The SASS files are compiled every time there is a change and generate the `.css` file in the `dist/` folder. To do that we add a 'start' script.

```
$ npm run start
```

**Run test.**

Run [sass-lint](https://github.com/sasstools/sass-lint) test using:

```
$ npm run test
```

**SASS compile.**

To directly compile the SASS files and generate the `.css` and `.min.css` files in the `dist/` folder by running the following command:

```
$ npm run build
```


## Browser support

- Chrome latest
- Firefox latest
- Opera latest
- Safari latest
- IE latest


## Contribute

Finding bugs, sending pull requests or improving our docs - any contribution is welcome and highly appreciated. To get started, head over to our [contribution guidelines](./contributing.md). Thanks!

## License

**.Lisi** is under the [MIT](./license.md) license. &copy; **Maare Studio**.
