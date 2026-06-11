![Moonfly Theme Preview](https://raw.githubusercontent.com/bluz71/misc-binaries/master/headings/moonfly.png)

A dark theme for Zed featuring an ultra-dark background, vibrant syntax highlighting, and a carefully balanced color palette optimized for long coding sessions.

![Banner](https://raw.githubusercontent.com/mirrrjr/zed-moonfly-theme/refs/heads/master/screenshot/banner.png)

## Features

* Deep black background (`#080808`)
* Low visual noise
* Italic comments
* Consistent syntax highlighting
* Carefully balanced ANSI terminal colors
* Optimized for PHP, Laravel, JavaScript, TypeScript, Vue, React, Rust, Go, and other modern languages

## Preview

| Element    | Color     |
| ---------- | --------- |
| Background | `#080808` |
| Foreground | `#bdbdbd` |
| Keywords   | `#cf87e8` |
| Functions  | `#80a0ff` |
| Strings    | `#8cc85f` |
| Types      | `#74b2ff` |
| Numbers    | `#ae81ff` |
| Operators  | `#85dc85` |
| Comments   | `#323437` |
| Variables  | `#bdbdbd` |
| Tags       | `#ff5d5d` |
| Links      | `#79dac8` |

## Installation

### Manual

```sh
mkdir -p ~/.config/zed/themes
cp moonfly.json ~/.config/zed/themes/
```

Then select the theme in your Zed settings:

```json
{
  "theme": "Moonfly"
}
```

## Terminal Palette

| Color   | Normal    | Bright    |
| ------- | --------- | --------- |
| Black   | `#323437` | `#949494` |
| Red     | `#ff5d5d` | `#ff5189` |
| Green   | `#8cc85f` | `#36c692` |
| Yellow  | `#e3c78a` | `#c6c684` |
| Blue    | `#80a0ff` | `#74b2ff` |
| Magenta | `#EE64AC` | `#F075B5` |
| Cyan    | `#79dac8` | `#85dc85` |
| White   | `#c6c6c6` | `#e4e4e4` |

## Credits

* Original Moonfly color palette by [bluz71](https://github.com/bluz71/vim-moonfly-colors)
* Ported and adapted for Zed
