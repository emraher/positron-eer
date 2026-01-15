# Positron +1e

## An Extension Pack for Positron

This is a lightly-opinionated extension pack for [Positron](https://github.com/posit-dev/positron), a next-generation data science IDE.

These are extensions I use in my daily work and that I feel round out the Positron experience. The extensions lean towards git-backed data science and dev work shared primarily on GitHub. 

The extensions are also great in VS Code (or any other VS Code-based IDE), but the pack is optimized for Positron in two ways:

1. All extensions are available on the [Open VSX Registry](https://open-vsx.org/), the open-source VS Code extension registry, and are licensed to be used outside of VS Code.
2. More than a few extensions that I use and need in VS Code _aren't on the list_ because Positron already provides native support for them. (Many R and Python extensions, for example.)

Recommendations, suggestions, comments and PRs are welcome!

## Installation

### Install from Releases

1. Download the latest `.vsix` file from the [Releases page](https://github.com/emraher/positron-eer/releases)
2. Open Positron
3. Open the Extensions view (Cmd+Shift+X on macOS, Ctrl+Shift+X on Windows/Linux)
4. Click the "..." menu at the top of the Extensions panel
5. Select "Install from VSIX..."
6. Navigate to and select the downloaded `.vsix` file
7. Reload Positron when prompted

All extensions in the pack will be automatically installed.

### Install from Command Line

```bash
positron --install-extension positron-plus-1-e-<version>.vsix
```

Replace `<version>` with the version number you downloaded (e.g., `0.1.0`).

## Extensions

**Note**: This pack excludes extensions that come bundled with Positron by default (Ruff, Pyrefly, Jupyter suite, Shiny, Publisher, Air, Quarto, and GitHub Pull Requests), avoiding unnecessary duplication.

### Project Management

-  [alefragnani.project-manager](https://open-vsx.org/extension/alefragnani/project-manager) - Quickly open and switch between projects. Pairs very well with the [Project Manager extension](https://www.raycast.com/MarkusLanger/vscode-project-manager) for [Raycast](https://www.raycast.com/).
-  [brunnerh.file-properties-viewer](https://open-vsx.org/extension/brunnerh/file-properties-viewer) - View file properties without having to open the file.
-  [eamodio.gitlens](https://open-vsx.org/extension/eamodio/gitlens) - Supercharge Git in Visual Studio Code with advanced views, powerful actions, and more.
-  [github.vscode-github-actions](<https://open-vsx.org/extension/github/vscode-github-actions>) - View and open GitHub Actions directly from the sidebar.
-  [gruntfuggly.todo-tree](https://open-vsx.org/extension/gruntfuggly/todo-tree) - A quick and easy way to find and manage your TODO's, FIXME's, etc.
-  [mhutchie.git-graph](https://open-vsx.org/extension/mhutchie/git-graph) - A graphical interface for viewing Git commit history and more.

### Python

-  [ms-pyright.pyright](https://open-vsx.org/extension/ms-pyright/pyright) - A static type checker for Python.

### Other languages and helpers

-  [mikestead.dotenv](https://open-vsx.org/extension/mikestead/dotenv) - `.env` syntax higlighting.
-  [ms-vscode.live-server](https://open-vsx.org/extension/ms-vscode/live-server) - Launch a local development server with a live reload feature for static and dynamic pages.
-  [pucelle.vscode-css-navigation](https://open-vsx.org/extension/pucelle/vscode-css-navigation) - Adds "Go to Definition", peeking and autocomplete for CSS and Sass files.
-  [redhat.vscode-yaml](https://open-vsx.org/extension/redhat/vscode-yaml) - Improves YAML support with validation, document outlining, autompletion, formatting and more.
-  [stkb.rewrap](<https://open-vsx.org/extension/stkb/rewrap>) - Rewrap text by wrapping the current line at a configurable column width.
-  [streetsidesoftware.code-spell-checker](https://open-vsx.org/extension/streetsidesoftware/code-spell-checker) - A basic, code-aware spell checker.

### Themes and Color

-  [bierner.color-info](https://open-vsx.org/extension/bierner/color-info) - Displays color information for a given color code.
-  [github.github-vscode-theme](https://open-vsx.org/extension/github/github-vscode-theme) - The official GitHub Visual Studio Code theme.
-  [gvelasq.tomorrow-night-bright-r-classic](https://open-vsx.org/extension/gvelasq/tomorrow-night-bright-r-classic) - A theme inspired by Posit's implementation of the Tomorrow Night Bright theme in the RStudio IDE.
-  [mechatroner.rainbow-csv](https://open-vsx.org/extension/mechatroner/rainbow-csv) - Highlights CSV files in different colors.
-  [johnpapa.vscode-peacock](https://open-vsx.org/extension/johnpapa/vscode-peacock) - Subtly customize IDE appearance to differentiate between different project windows.

## Additional Extensions

### Additional Themes

-  [catppuccin.catppuccin-vsc](https://open-vsx.org/extension/catppuccin/catppuccin-vsc) - Soothing pastel theme for Positron with warm and cool color variants.
-  [dracula-theme.theme-dracula](https://open-vsx.org/extension/dracula-theme/theme-dracula) - Dark theme with vibrant, contrasting colors inspired by the Dracula color scheme.
-  [pkief.material-icon-theme](https://open-vsx.org/extension/pkief/material-icon-theme) - Material Design icons for your file explorer with extensive file type coverage.

### Package Management

-  [ntluong95.positron-python-package-manager](https://open-vsx.org/extension/ntluong95/positron-python-package-manager) - Manage Python packages directly within Positron.

-  [kv9898.positron-r-package-manager](https://open-vsx.org/extension/kv9898/positron-r-package-manager) - Manage R packages directly within Positron.

### Development Tools

-  [aaron-bond.better-comments](https://open-vsx.org/extension/aaron-bond/better-comments) - Improve code commenting by highlighting different types of comments with different colors.
-  [DavidAnson.vscode-markdownlint](https://open-vsx.org/extension/DavidAnson/vscode-markdownlint) - Markdown linting and style checking for consistent documentation.
-  [GrapeCity.gc-excelviewer](https://open-vsx.org/extension/GrapeCity/gc-excelviewer) - View Excel spreadsheets and CSV files directly in the editor.
-  [ms-azuretools.vscode-docker](https://open-vsx.org/extension/ms-azuretools/vscode-docker) - Create, manage, and debug containerized applications with Docker support.
-  [robole.file-bunny](https://open-vsx.org/extension/robole/file-bunny) - Quick file operations and navigation shortcuts for improved productivity.
-  [rpinski.shebang-snippets](https://open-vsx.org/extension/rpinski/shebang-snippets) - Code snippets for shebang lines in various scripting languages.
-  [SamEdwardes.right-click-open-here](https://open-vsx.org/extension/SamEdwardes/right-click-open-here) - Right-click context menu to open files and folders in Positron.
-  [sumneko.lua](https://open-vsx.org/extension/sumneko/lua) - Lua language support with rich features including intellisense, diagnostics, and more.
