<!--
Welcome to this README template!

To help you navigate, in any section you want to edit, I've put a comment written EDIT.

Have fun!
-->

<p align="center">
  <h3 align="center">Postcss Template</h3> <!-- EDIT -->
  <p align="center">
    A PostCSS template for when you quickly need to add styling to your project. <!-- EDIT -->
  </p>
  <!-- EDIT: Head over to https://shields.io/ to generate some beautiful shields! -->
  <p align="center">
    <a href="https://github.com/TGlide/README-TEMPLATE">
      <img src="https://img.shields.io/badge/Built with-PostCSS-%23000000?style=for-the-badge&logo=read-the-docs" alt="Built with PostCSS">
    </a>
  </p>
</p>

<!-- EDIT: TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)

<!-- EDIT: ABOUT THE PROJECT -->

## About The Project

This template contains a styles folder, a postcss.config.js file and a package.json file. Inside the styles folder, you'll find an index file, which you can directly import to use within your project. There's also a .vscode folder with settings and extension reccomendations for CSS var auto-completion.

## PostCSS Plugins
- [postcss-extend-rule](https://github.com/csstools/postcss-extend-rule): Extends one CSS rule to another. May require some additional config to make it work with your project. e.g. in Vue SFC style tags, you need to import a file that contains or imports the class you want to extend.
- [postcss-preset-env](https://github.com/csstools/postcss-preset-env): Allows you to use modern CSS syntax, converting it to something that's compatible with your target browsers.

## Style directory structure

### `index.pcss`
Main file, which you can import directly to use within your project.

### `tokens.pcss`
Contains CSS variables, which you can use throughout your project.

### `theme.pcss`	
Contains theme classes, with their own CSS variables.

### `reset.pcss`
Contains CSS reset.

### `fonts.pcss`
A file to include font-face declarations.

### `animations.pcss`
A file to include animations.

### `components/index.pcss`
Imports the other files in the components folder.

### `components/link.pcss`
Contains some example classes for link-related components.

### `components/layout.pcss`
Contains some example classes for layout-related components.

### `utility/index.pcss`
Imports the other files in the utility folder.

### `utility/colors.pcss`
Contains some example classes for color-related utility classes.

### `utility/display.pcss`
Contains some example classes for display-related utility classes e.g. `block`, `flex`.

### `utility/media.pcss`
Contains some example classes for media-related utility classes e.g. `lg`, `hidden-lg`.

### `utility/position.pcss`
Contains some example classes for position-related utility classes e.g. `absolute`, `fixed`.

### `utility/spaces.pcss`
Contains some example classes for space-related utility classes e.g. `m-0`, `py`.

### `utility/typography.pcss`
Contains some example classes for typography-related utility classes e.g. `text-center`, `text-2xl`.





