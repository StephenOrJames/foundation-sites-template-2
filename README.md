# Foundation for Sites Template (custom)

This is a custom template for using [Foundation for Sites](https://foundation.zurb.com/sites) based on [the official starter template](https://github.com/zurb/foundation-sites-template) and [the official ZURB template](https://github.com/zurb/foundation-zurb-template). It is more advanced than the starter template, but only provides *some* of the tasks offered by the ZURB template. The structure used for folder organization is also different.


## Features

This template includes the following:
- Sass compiler (with autoprefixer) and CSS compression
- JavaScript concatenation and compression
- Image compression


## Requirements

To use this template, you will need:
- [Git](https://git-scm.com/)
- [NodeJS](https://nodejs.org/en/) (with [npm](https://www.npmjs.com/))
- [Bower](https://bower.io/)


## Setting up

To set up the template for your project:
- Clone this repository: `git clone https://github.com/StephenOrJames/foundation-sites-template-2.git your_folder`
- Enter the folder: `cd your_folder`
- Install the dependencies:
  - NPM: `npm install`
  - Bower: `bower install`
- Start the Gulp build system: `npm start`


## Getting to work

Once you've set up the template, you should have a folder structure similar to the following:

- your_folder
  - bower_components
  - dist
    - css
    - img
    - js
  - node_modules
  - src
    - img
    - js
    - scss

Your files will be added to the respective folders within `src`, and will be compiled and/or compressed into `dist`. Note that the output files for CSS and JavaScript will be app.css and app.js respectively.

**Note: Any file manually placed in `dist` may be deleted, as a part of the build process includes deleting `dist`.**
