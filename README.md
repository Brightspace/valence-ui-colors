**Looking for SASS-based `d2l-colors`?** It’s [over here](https://github.com/Brightspace/d2l-colors-ui/tree/sass).

# d2l-colors

[![Bower version][bower-image]][bower-url]
[![Build status][ci-image]][ci-url]

This component contains a [Polymer](https://www.polymer-project.org/1.0/) web component for the D2L color palette.

For further information on this and other D2L UI components, see the docs at [ui.valence.d2l.com](http://ui.valence.d2l.com/).

## Installation

`d2l-colors` can be installed from [Bower][bower-url]:

```shell
bower install d2l-colors
```

## Usage

Include the [webcomponents.js](http://webcomponents.org/polyfills/) "lite" polyfill (for browsers who don't natively support web components), then import `d2l-colors.html`.

```html
<head>
	<script src="https://s.brightspace.com/lib/webcomponentsjs/0.7.21/webcomponents-lite.min.js"></script>
	<link rel="import" href="../d2l-colors/d2l-colors.html">
</head>
```

By including the D2L color's [shared style](https://www.polymer-project.org/1.0/docs/devguide/styling#style-modules), you can reference the color variables in your CSS:

```html
<head>
	<style is="custom-style" include="d2l-colors">
		div {
			background-color: var(--d2l-color-saphirella);
		}
	</style>
</head>
```

The list of available color variable names is [in the source](https://github.com/Brightspace/d2l-colors-ui/tree/master/d2l-colors.html).

## Coding styles

See the [Best Practices & Style Guide](https://github.com/Brightspace/valence-ui-docs/wiki/Best-Practices-&-Style-Guide) for information on naming conventions, plus information about the [EditorConfig](http://editorconfig.org) rules used in this repo.

[bower-url]: http://bower.io/search/?q=d2l-colors
[bower-image]: https://img.shields.io/bower/v/d2l-colors.svg
[ci-url]: https://travis-ci.org/Brightspace/d2l-colors-ui
[ci-image]: https://travis-ci.org/Brightspace/d2l-colors-ui.svg?branch=master
