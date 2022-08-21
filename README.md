# HTML5 Template + webpack + Less (Boilerplate + Build tool)

HTML5 template with webpack, Less, JavaScript, images, and fonts support.
The build tool is included (CSS and JS optimization support).

## Prerequisites

- Node.js
- npm

## Installation

```npm install```

## Scripts

### Run project/server

``` npm run app ```

### Build project

Build project into the ```dist``` output directory.

``` npm run build ```

### Compile less file

``` npm run less-compile ```

### Watch less files

``` npm run less-watch ```

## Run build/production version

Run index.html file (dist/index.html).
You can use the Live server to run index.html.

## Configuration

### npm 
#### JavaScript entry point

Edit package.json file.

Change the entry point here.

``` "main": "src/js/script.js",```

### webpack
#### Output directory

Edit webpack.config.js file.

Change the output directory here.

```path: path.resolve(__dirname, "dist"),```
