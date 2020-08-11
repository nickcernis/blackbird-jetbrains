<p align="center">
  <img src="docs/blackbird-logo.png" alt="Blackbird theme">
</p>

<p align="center">The Blackbird theme for <a href="https://www.jetbrains.com/products.html#type=ide">JetBrains IDEs</a>.</p>

--- 

## The high-contrast dark theme for spellcasters

![Screenshot showing React and CSS syntax highlighting.](docs/screenshots/react-css.png) 


![Screenshot showing Rust and JSON syntax highlighting with IDE Screenshot showing Rust and JSON syntax highlighting with IDE chrome turned off.](docs/screenshots/rust-json-no-chrome.png)

### Why try Blackbird?

- **High readability** with a contrast ratio of 7:1 or better for editor text (WCAG Level AAA).
- **A simple palette** to reduce visual overload in the editor.
- **Good default font settings** with JetBrains Mono at size 15 and 1.1 line spacing. No italics. Ligatures in the editor but not in the terminal.
- **Reduced distractions** with stripe marks for errors only, instead of for errors, warnings, weak warnings, and others. 
- **Text editor looks** with a unified background color and minimal borders.
- **Lightweight** implementation as a pure theme with no plugin requirements.

### Advice for minimalists

- Turn off the toolbar, navigation bar, and tool window bars (View → Appearance). 
- Turn off tabs (Editor → General → Tabs → Tab Placement → none). Then navigate with Search Everywhere (Shift Shift), Recent Files (Ctrl/Cmd + E), or set up [IdeaVim bindings to cycle through tabs/buffers](https://gist.github.com/nickcernis/bcb5cb7f55c07ed3de8287d163ed7c28#file-ideavimrc-L55-L58).
- Keep the Project tool window closed unless you need a tree view. 

### Change the default font
1. Uncheck “Use color scheme font…” at Editor → Color Scheme → Color Scheme Font. 
2. Set your font at Editor → Font.

### Credits

- Blackbird name and color scheme inspired by the [Blackbird comic](https://imagecomics.com/comics/releases/blackbird-2) artwork by Jen Bartel.
- Background color and aesthetic inspired by the [Night Owl theme](https://github.com/sdras/night-owl-vscode-theme) by Sarah Drasner.
- “Blackbird“ (Raven) icon by [Imogen Oh](https://www.iconfinder.com/Imogen.Oh), licensed via Iconfinder.
- The Blackbird header in this readme is set in [Flood Std Regular](https://fonts.adobe.com/fonts/flood) by Joachim Müller-Lancé.

### Color palette

| Color | Native (JetBrains) | sRGB (Electron/VS Code/iTerm) |
|---|---|---|
| ![midnight color](docs/colors/011528.png) midnight | #051527| #011528 |
| ![portal color](docs/colors/79efc4.png) portal | #97ecc7 | #79efc4 |
| ![nevermore color](docs/colors/00b8b4.png) nevermore | #34b5b3 | #00b8b4 |
| ![potion color](docs/colors/ff639d.png) potion | #ff709d | #ff639d |
| ![obliterate color](docs/colors/fff500.png) obliterate| #fff423 | #fff500 |
| ![spirit color](docs/colors/ffffff.png) spirit | #ffffff | #ffffff |
| ![limbo color](docs/colors/8695ae.png) limbo | #8995ac | #8695ae |

For tints and other colors see `resources/Blackbird.theme.json` and `resources/Blackbird.xml`. Colors in these files use native color space. You will need to convert to sRGB if designing for an application that uses sRGB color space. On Mac, the Digital Color Meter can help to determine the app's color space.
