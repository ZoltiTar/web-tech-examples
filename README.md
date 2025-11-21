# Web Technologies Examples

---
### Other assignments/labs: https://github.com/poszetkristof/web_tech_examples
---
## XML and CSS

### 09/25
* Assignment 1: [album](/album) 
* Assignment 2: [book](/book)

### 10/02
* Assignment 1: [menu](/menu) 
* Assignment 2: [movies](/movies)

## Sass

### 11/13
 - Install Node.js/NPM:
   * Through the official site: https://nodejs.org/en/download
   * Through a version manager of choice, for example: [fnm](https://github.com/Schniz/fnm), [nvm](https://github.com/nvm-sh/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows)
   * Test Node and npm by running `node -v` and `npm -v`
 - Install sass:
   * `npm install -g sass` - installs sass globally (if you don't use the global `-g` flag, it will only get installed in the your current folder and it will init the folder with package.json and node_modules)
   * Note: if you are using a node version manager, when installing packages it will only be available on the currently active node version
   * Test sass by running `sass -v`
 - Compile your sass stylesheet with `sass <input.scss> <output.scss>`
   * use the [--watch](https://sass-lang.com/documentation/cli/dart-sass/#watch) flag to compile whenever your file changes
 - Full Sass documentation: https://sass-lang.com/documentation/

* Assignment 1: [colors](/colors)
  - You can find an extra, ['overengineered'](/colors/colors-complex.scss) solution that showcases some additional sass features like: flow control, mixins and maps.  
* Assignment 2: [color-transition](/color-transition)
