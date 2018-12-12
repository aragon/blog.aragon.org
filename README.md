# Aragon blog theme

Based on Casper, the default theme for [Ghost](http://github.com/tryghost/ghost/).

&nbsp;

# Development

Compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

```bash
$ yarn install
$ yarn dev
```

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
$ yarn zip
```
