# Cascadios Code

Cascadios is a fork of [Cascadia Code](https://github.com/microsoft/cascadia-code) that features a set of non-intrusive ligatures, as well as full Nerd Font support.

## Why Cascadios?

I like many of the ligatures in Cascadia Code, such as `(*` and `...` that make the font more pleasing to the eye. However, I could never get behind some of the more heavily altered ligatures, such as `<=`. Thus, Cascadios was born as a way of using the less dramatic ligatures without drastically changing the look of the base font.

## Font features

![Coding Ligatures](images/ligatures.png)

> Cascadios does not use arrow and (in)equality ligatures because they can make it difficult to distinguish individual characters.

![Arrow Support](images/arrow_support.png)

![Stylistic Sets](images/stylistic_set.png)

> Cascadios uses the slashed zero by default (like Cascadia Mono) instead of the dotted zero (like Cascadia Code).

Enabling stylistic sets will [vary between applications](https://github.com/tonsky/FiraCode/wiki/How-to-enable-stylistic-sets). For example, in VS Code, you can enable stylistic sets (and other OpenType features) via `settings.json`:

```
"editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'"
```

## Nerd Font Support

Check out Nerd Fonts here! <https://www.nerdfonts.com>

Cascadios uses the patching workflow from [Delugia Code](https://github.com/adam7/delugia-code).

#### To enable the Cursive form of the italic, here's the code you should use:

```
"editor.fontLigatures": "'calt', 'ss01'",
```
If you're using an environment that does not support the `ss01` OT feature, one option to consider is [opentype-feature-freezer](https://github.com/twardoch/fonttools-opentype-feature-freezer/).

## Character Sets

![Cascadia Code](images/cascadia-code-characters.png)
![Cascadia Code Italic](images/cascadia-code-italic-characters.png)

## Installation

**You can download the latest version of Cascadia Code from the releases page here:** [https://github.com/microsoft/cascadia-code/releases](https://github.com/microsoft/cascadia-code/releases)

##### Font formats:

- `ttf static`: This is the only option due to limiations in the NerdFonts patcher.

Once unzipped, right-click the font file and click `Install for all users`. This will install the font onto your machine. 

👉 **Note:** If you have previously installed a version of Cascadia Code, please uninstall the previous version *prior* to installing a new version. Not doing so can result in improper rendering. 

