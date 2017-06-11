# Atom Material Palenight Syntax

:new_moon: An elegant and minimal material syntax theme for Atom.

![Theme Preview](http://i.imgur.com/L7BJvfv.png)

_Shown with [Atom Material UI][1]. The fonts used in the screenshot are [Fira Code](https://github.com/tonsky/FiraCode) and [Operator Mono](http://www.typography.com/fonts/operator)._

## Installation
If you're a terminal guru :ghost:, launch a window and type:
```shell
apm install material-palenight-syntax
```
**There's also a [VS Code version](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme) of this theme created by [me](https://twitter.com/whizkydee).**

Or, inside Atom's settings select Install and then search for this syntax theme.

## Recommended UI Themes

Some UI themes that work best with this syntax theme.

* [Atom Material UI][1] &ndash; Awesome! 'twas made for it.
* [Pristine UI][2] &ndash; It's gorgeous!
* [One Dark UI][3] &ndash; Looks great.

## Tweaks
:v: If you're using [Atom Material UI][1], add the following lines to your Atom Config (config.cson) file for an awesome experience:

``` coffee
"atom-material-ui":
  colors:
    abaseColor: "#7e57c2"
    accentColor: "#ffffff"
    paintCursor: true
    predefinedColor: "Purple"
  tabs: {}
  treeView:
    blendTabs: true
    compactList: false
  ui:
    panelShadows: true
```

Also, if you have [Operator Mono](http://www.typography.com/fonts/operator) font installed, add the following lines to your stylesheet (styles.less) file to experience the beauty of its italic style:

``` css
atom-text-editor {
  -webkit-font-feature-settings: "liga" off, "calt" off; /* very mandatory */
  text-rendering: optimizeLegibility; /* cool */
  font-weight: normal; /* for specificity */
  line-height: 1.7; /* feel free to adjust */
}
.syntax--doctype, .syntax--entity.syntax--other.syntax--attribute-name, .syntax--source.syntax--js.syntax--jsx > .syntax--keyword.syntax--control.syntax--flow.syntax--js,
.syntax--punctuation.syntax--section.syntax--embedded, .syntax--keyword:not(.syntax--logical):not(.syntax--arithmetic):not(.syntax--bitwise):not(.syntax--increment):not(.syntax--ternary):not(.syntax--comparison),
.syntax--meta.syntax--structure.syntax--dictionary.syntax--key.syntax--json,
.syntax--storage, .syntax--italic, .syntax--language, .syntax--type .syntax--function,
.syntax--type.syntax--function, .syntax--storage.syntax--type.syntax--class, .syntax--type.syntax--var, .syntax--meta.syntax--parameter, .syntax--assignment.syntax--coffee, .syntax--keyword.syntax--control, .syntax--modifier, .syntax--boolean, .syntax--null,
.syntax--this, .syntax--comment {
  font-family: "Operator Mono Light"; /* varies with font name */
  vertical-align: inherit; /* just keep it */
  font-style: italic; /* mandatory */
  line-height: 10px; /* Optional */
}
```

[1]: https://atom.io/themes/atom-material-ui
[2]: https://atom.io/themes/pristine-ui
[3]: https://atom.io/themes/one-dark-ui

## Wanna Contribute?
Feel free to report [here](https://github.com/whizkydee/material-palenight-syntax/issues) any suggestions or irregular syntax highlighting of this theme with an attached screenshot or source file where necessary.

## License
This theme is released under the [MIT License](https://github.com/whizkydee/atom-material-palenight-syntax/blob/master/LICENSE.md).

Designed with :heart: by [Olaoluwa](https://whizkydee.github.io). Follow him on [GitHub](https://github.com/whizkydee)
