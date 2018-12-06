**ux-core-styles**
========

[View Demo](https://pages.github.homedepot.com/ux/ux-core-styles/examples.html)  

Standardized styles for Typography, Cards, Colors and Buttons provided by Home Depot UX.
- Also utilizes uxicon font package.

**To utilize CSS via URL**
- For **CURRENT VERSION** include `https://pages.github.homedepot.com/ux/ux-core-styles/dist/ux-core-styles.min.css` in your project  
- For **SPECIFIC VERSION (starting with 1.9.0)** include `https://pages.github.homedepot.com/ux/ux-core-styles/dist/VERSION/ux-core-styles.min.css` in your project

**To install via NPM**
- Run `npm install ux-core-styles --save-dev`
    - Ensure your npm registry is pointing to https://npm.artifactory.homedepot.com/artifactory/api/npm/npm

**To install via Bower**
- Run `bower install ux-navigation --save-dev`
    - Run `npm install -g bower-art-resolver` and add `resolvers` array to `.bowerrc`
    - Ensure your bower registry is pointing to https://bower.artifactory.homedepot.com/artifactory/api/bower/bower
    - Please reference this project's `.bowerrc` for an example

**After installing perform the following**
- Include `dist/ux-core-styles.min.css` for CSS (either in a `<style>` tag or compiled with other files) or use files located in `src` for SASS (if you want to make further modifications)
- **OPTIONAL**: `dist/ux-core-styles.css`, an un-minified CSS file is available to use instead of minified version
- **OPTIONAL**: If utilzing SASS, import `src/base.scss` for the main SASS file as it imports all other SASS files

**To run locally from GitHub**
- Run `npm install`
- Run `gulp` to generate un-minified `ux-core-styles.css` and minified `ux-core-styles.min.css` CSS from SASS files
