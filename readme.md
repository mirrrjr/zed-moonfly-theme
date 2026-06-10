# Moonfly Theme for Zed

A dark theme for Zed inspired by the original Moonfly color scheme by bluz71. It features an ultra-dark background, low-contrast UI surfaces, vibrant syntax highlighting, and carefully balanced accent colors designed for long coding sessions.

## Preview

| Element | Color |
|----------|----------|
| Background | `#0e0e0e` |
| Foreground | `#D5D8DA` |
| Keywords | `#cf87e8` |
| Functions | `#80a0ff` |
| Strings | `#8cc85f` |
| Types | `#74b2ff` |
| Numbers / Constants | `#ae81ff` |
| Operators | `#85dc85` |
| Comments | `#323437` (italic) |
| Variables | `#bdbdbd` |
| HTML / JSX Tags | `#ff5d5d` |
| Attributes | `#cf87e8` |
| Special Variables | `#ff5189` |
| Links | `#79dac8` |
| Errors | `#F43E5C` |
| Warnings | `#27D797` |

## Features

- Ultra-dark `#0e0e0e` background
- Low-contrast UI elements
- Italic comments
- Vibrant syntax highlighting
- Consistent terminal palette
- Optimized for PHP, Laravel, JavaScript, TypeScript, Vue, React, Rust, Go, and other modern languages
- Moonfly-inspired color balance with Zed-native styling

## Installation

### Manual Installation

1. Create the themes directory if it doesn't exist:

   ```sh
   mkdir -p ~/.config/zed/themes
   ```

2. Copy the theme file:

   ```sh
   cp moonfly.json ~/.config/zed/themes/
   ```

3. Open Zed settings and select the theme:

   ```json
   {
     "theme": "Moonfly"
   }
   ```

4. Reload Zed.

## UI Colors

| Component | Color |
|------------|------------|
| Editor Background | `#0e0e0e` |
| Surface Background | `#0e0e0e` |
| Elevated Surface | `#0E0E0E` |
| Active Line | `#080808` |
| Selection / Match | `#a42aeb3d` |
| Panel Background | `#0E0E0E` |
| Element Background | `#2E303E` |
| Focus Border | `#1A1C23` |
| Accent | `#E95378` |

## Syntax Palette

| Token | Color |
|--------|--------|
| Keyword | `#cf87e8` |
| Function | `#80a0ff` |
| Type | `#74b2ff` |
| String | `#8cc85f` |
| Number | `#ae81ff` |
| Constant | `#ae81ff` |
| Variable | `#bdbdbd` |
| Parameter | `#bdbdbd` |
| Property | `#bdbdbd` |
| Operator | `#85dc85` |
| Punctuation | `#85dc85` |
| Tag | `#ff5d5d` |
| Attribute | `#cf87e8` |
| Comment | `#323437` |
| Documentation Comment | `#323437` |
| Link | `#79dac8` |

## Terminal Palette

| Color | Normal | Bright |
|--------|--------|--------|
| Black | `#06060C` | `#141414` |
| Red | `#E95678` | `#EC6A88` |
| Green | `#29D398` | `#3FDAA4` |
| Yellow | `#FAB795` | `#FBC3A7` |
| Blue | `#26BBD9` | `#3FC4DE` |
| Magenta | `#EE64AC` | `#F075B5` |
| Cyan | `#59E1E3` | `#6BE4E6` |
| White | `#D5D8DA` | `#D5D8DA` |

<!--## Screenshot

Add screenshots here after publishing the theme.-->

## Credits

- Original Moonfly colors by bluz71
- Adapted and customized for Zed
- Built using the Zed Theme Schema v0.2.0
