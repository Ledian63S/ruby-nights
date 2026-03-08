<div align="center">

<img src="icon.png" width="120" alt="Ruby Nights" />

# Ruby Nights

A dark VS Code theme with rich ruby and garnet tones. Easy on the eyes for long coding sessions, with warm dark backgrounds and four variants to match your preference.

[![Version](https://img.shields.io/visual-studio-marketplace/v/lekaledian.ruby-nights?label=Marketplace&color=8a3040)](https://marketplace.visualstudio.com/items?itemName=lekaledian.ruby-nights)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/lekaledian.ruby-nights?color=8a3040)](https://marketplace.visualstudio.com/items?itemName=lekaledian.ruby-nights)

</div>

---

![Screenshot](screenshot.png)

## Variants

| Name | Description |
|------|-------------|
| **Ruby Nights** | Warm dark ruby tones — darker sidebar, lighter editor |
| **Ruby Nights Midnight** | Deeper, darker ruby for low-light environments |
| **Ruby Nights Garnet** | Rich wine and burgundy tones with a subtle purple hint |
| **Ruby Nights Garnet Midnight** | Deeper garnet for maximum depth and contrast |

## Features

- Warm ruby and garnet background tones — comfortable for long coding sessions
- Gold (`#e6b450`) accent color for cursor, badges, and highlights
- Clear git status colors — sage green for modified, red for deleted, light for untracked
- Distinct sidebar and editor backgrounds for clear visual separation
- Subtle line highlight and bracket match colors that don't distract
- Readable inactive tabs, breadcrumbs, and status bar

## Install

1. Open VS Code
2. Go to **Extensions** (`Ctrl+Shift+X`)
3. Search for `Ruby Nights`
4. Click **Install**
5. Open the Command Palette (`Ctrl+Shift+P`) → **Preferences: Color Theme** → select your variant

## Recommended Setup

For the best experience, add these to your VS Code `settings.json`:

```json
{
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontLigatures": true,
    "editor.cursorBlinking": "expand",
    "editor.bracketPairColorization.enabled": false,
    "editor.semanticHighlighting.enabled": true,
    "workbench.iconTheme": "vscode-icons",
    "workbench.productIconTheme": "fluent-icons"
}
```

> **JetBrains Mono** can be downloaded from [jetbrains.com/mono](https://www.jetbrains.com/mono/).
> **vscode-icons** and **fluent-icons** are free extensions available in the VS Code Marketplace.

## Contribute

1. Clone the repo and open it in VS Code
2. Press `F5` to launch the Extension Development Host
3. Modify the theme files in `./themes/`
4. Open a new file in the development host to preview changes

## License

[Apache-2.0](LICENSE)
