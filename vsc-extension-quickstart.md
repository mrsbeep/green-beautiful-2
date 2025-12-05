# Green Beautiful Color Themes - Quick Start Guide

Welcome to the **Green Beautiful Color Themes** extension! This extension provides 11 stunning color themes for Visual Studio Code, ranging from dark and vibrant to light and high-contrast options.

## What's in the folder

- This folder contains all of the files necessary for your color theme extension.
- `package.json` - this is the manifest file that defines the location of the theme files and specifies the base theme of each theme.
- `themes/` - contains all color theme definition files (JSON format).
- `screenshots/` - preview images of all available themes.
- `icons/` - extension icon and assets.

## Available Themes

This extension includes 11 carefully crafted themes:

### Dark Themes

- **Green Dark** - A soothing dark theme with green accents
- **Green Beautiful 2** - Enhanced dark theme with balanced green tones
- **Ocean Deep** - Deep blue oceanic theme for calm coding sessions
- **Crimson Night** - Rich dark theme with crimson highlights
- **Violet Dusk** - Dark theme with elegant violet accents
- **Golden Sunset** - Warm dark theme with golden hues
- **Sky Breeze** - Cool dark theme with sky blue tones

### Light Themes

- **Lavender Breeze** - Soft light theme with lavender tones
- **Amber Glow** - Warm light theme with amber highlights

### High Contrast Themes

- **Azure HC** - High contrast dark theme with azure accents
- **Rose Petal HC** - High contrast theme with rose pink tones

## Theme Previews

### Green Beautiful 2

![Green Beautiful 2](screenshots/green-beautiful-2.png)

### Green Dark

![Green Dark](screenshots/green-dark.png)

### Ocean Deep

![Ocean Deep](screenshots/ocean-deep.png)

### Crimson Night

![Crimson Night](screenshots/crimson-night.png)

### Lavender Breeze

![Lavender Breeze](screenshots/lavender-breeze.png)

### Amber Glow

![Amber Glow](screenshots/amber-glow.png)

### Azure HC

![Azure HC](screenshots/azuer-hc.png)

### Violet Dusk

![Violet Dusk](screenshots/violet-dusk.png)

### Golden Sunset

![Golden Sunset](screenshots/golden-sunset.png)

### Sky Breeze

![Sky Breeze](screenshots/sky-breeze.png)

### Rose Petal HC

![Rose Petal HC](screenshots/rose-petal-hc.png)

## Get up and running straight away

- Press `F5` to open a new window with your extension loaded.
- Open the color theme picker with the `File > Preferences > Theme > Color Theme` menu item, or use the `Preferences: Color Theme` command (`Ctrl+K Ctrl+T` on Windows/Linux or `Cmd+K Cmd+T` on Mac).
- Select one of the Green Beautiful themes from the list.
- Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

- Changes to the theme files are automatically applied to the Extension Development Host window.
- Edit any of the theme JSON files in the `themes/` folder to customize colors.
- Save the file and see the changes immediately reflected in the Extension Development Host.

## Adopt your theme to Visual Studio Code

- The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.
- Each theme file contains color definitions for:
  - UI elements (editor, sidebar, status bar, etc.)
  - Syntax highlighting tokens
  - Terminal colors
  - Git decorations
  - And more...

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

### Local Installation

- To start using your extension with Visual Studio Code, copy it into the `<user home>/.vscode/extensions` folder and restart Code.
- Alternatively, you can package the extension using `vsce package` and install the `.vsix` file.

### Publishing to Marketplace

- To share your extension with the world, read the [publishing guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) about publishing an extension.
- You'll need to create a publisher account on the Visual Studio Marketplace.
- Use `vsce publish` to publish your extension.

## Feedback and Contributions

Found a bug or have a suggestion? Please open an issue on our [GitHub repository](https://github.com/mrsbeep/green-beautiful-2).

Enjoy coding with Green Beautiful Color Themes! 🎨
