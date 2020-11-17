# Cobalt2 Theme for Panic Nova

**[WARNING]** This is a work in progress, none of the information below is accurate.




# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Cobalt2` - find the one by **Wes Bos** - there are a few other half-baked ones so make sure you have the right one!
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. Code > Preferences > Color Theme > **Cobalt2**
6. Optional: Use the recommended settings below for best experience

## Recommended Settings

```js
{
  "workbench.colorTheme": "Cobalt2",
  // The Cursive font is operator Mono, it's $200 and you need to buy it to get the cursive
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 17,
  "editor.lineHeight": 25,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "400",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  // Very important: Install this plugin: https://github.com/be5invis/vscode-custom-css
  // You'll need to change this to a file URI scheme on your computer: https://en.wikipedia.org/wiki/File_URI_scheme
  // Mac/Linux: file:///Users/YOUR-PC-USERNAME/.vscodestyles.css
  // Windows: file:///C:/Users/YOUR-PC-USERNAME/.vscodestyles.css
  "vscode_custom_css.imports": [
    "file:///Users/wesbos/.vscodestyles.css"
  ],
  "editor.renderWhitespace": "all",
}
```

## I don't like something

First, this theme is new so if something is funky, please open an issue.

These are the things we have control over. If you would like to change something, you can either open a PR and see if I'd like it added, or override the colours in your own settings.json file.

https://code.visualstudio.com/docs/getstarted/theme-color-reference

## Put Cobalt2 in other places!

* [Sublime Text](https://github.com/wesbos/cobalt2)
* [Atom](https://github.com/wesbos/Cobalt2-atom)
* [iTerm2](https://github.com/wesbos/Cobalt2-iterm)
* [Hyper Term](https://github.com/wesbos/hyperterm-cobalt2-theme)
* [Alfred](https://github.com/wesbos/Cobalt2-Alfred-Theme)
* [Slack](https://github.com/wesbos/Cobalt2-Slack)

## Thanks

Thanks to [Wes Bos](https://github.com/wesbos) for the original Cobalt2 template.
