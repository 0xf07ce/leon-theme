# Leon Theme

**Leon** is a collection of color themes for keeping a consistent look and feel across multiple editors. The JetBrains `.icls` schemes are the source of truth, and the other platform versions are maintained as ports.

## Contents

| Folder | Platform | Description |
|--------|----------|-------------|
| [`vscode/`](./vscode) | Visual Studio Code | Leon Light / Leon Dark theme extension |
| [`jetbrains/`](./jetbrains) | JetBrains IDEs (CLion, etc.) | `Leon_Light.icls`, `Leon_Dark.icls` (source schemes) |
| [`iterm/`](./iterm) | iTerm2 | `Leon_Light.itermcolors` |

## Installation

### VS Code

Install the `.vsix` file from [Releases](https://github.com/0xf07ce/leon-theme/releases), or run:

```bash
code --install-extension leon-theme-1.1.3.vsix
```

See [`vscode/README.md`](./vscode/README.md) for usage details, including theme selection and automatic switching with the OS color scheme.

### JetBrains

Open Settings -> Editor -> Color Scheme -> gear icon -> **Import Scheme...**, then select one of the `.icls` files in [`jetbrains/`](./jetbrains).

### iTerm2

Open Settings -> Profiles -> Colors -> **Color Presets... -> Import**, then select [`iterm/Leon_Light.itermcolors`](./iterm/Leon_Light.itermcolors).

## License

[MIT](./LICENSE)
