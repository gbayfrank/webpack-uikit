# Webpack UIKit

## Description

This project contains preconfigured Webpack 5 to work with the following tasks:

- Compile SCSS to CSS
- Optimize images (*.png, *.jpeg, *.gif)
- Convert SVG into inline 'data:image' format
- Fonts loader
- Automatic copy static directory to the dist directory
- Production optimization (styles, JavaScript, images)
- Build source maps

## Includes

- UIKit 3.9.4 (SCSS, JS)

## Installation

- Execute a command from the root directory
```
npm install
```
- Use 'index.html' as home page
- Write Your own JavaScript in the file: `development/js/app.js`
- Also Your styles may be placed in the SCSS file: `development/scss/app.scss`
- Then run the following command to build `dev` bundle:
```
npm run build
```
- **Good luck!**

## Project structure

- **development**: Project sources root
    - **images**: Images and icons used in your styles
    - **js**: JavaScript code-base for your application
    - **scss**: Styles sources (may contain structure what you like)
    - **static**: Images and media-files which uses statically (will be copied to the `dist` directory), ex: uses in the HTML

## Tasks

- Build sources - ```npm run build```
- Start file watcher for recompiling - ```npm run watch```
- Start webpack dev server - ```npm run start```
- Build sources for production (**with optimization**) - ```npm run production```
- Clean '`dist`' folder - ```npm run clear```