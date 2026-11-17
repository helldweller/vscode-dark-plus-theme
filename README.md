# VS Code Dark+ (full) for Orca

A full port of the VS Code **Dark+** theme for [Orca](https://github.com/stablyai/orca).

The bundled `VS Code Dark+` theme sets only 6 colors and leaves the rest to Orca's defaults. This one also covers:

- **App UI**: 32 tokens from VS Code's Dark+ workbench defaults (sidebar `#252526`, buttons `#0e639c`, focus ring `#007fd4`, list selection `#37373d`, muted text `#9d9d9d`, and so on).
- **Syntax**: Dark+ token colors.
- **Terminal**: VS Code's default dark ANSI palette, cursor and selection.

## Install

```sh
orca plugin install helldweller/vscode-dark-plus-theme
```

Then open Settings → Appearance and pick **VS Code Dark+ (full)** as the dark app theme and as the dark terminal theme.

To match VS Code's default Linux fonts, also set the editor and terminal font to `DejaVu Sans Mono` at 14px with weight 400. Set the UI font to your system font (for example `Ubuntu Sans`).

## Develop

```sh
orca plugin validate .
orca plugin dev watch .    # live-reloads this folder in Orca; Ctrl-C unloads it
```

## Attribution

Colors come from the VS Code [default themes](https://github.com/microsoft/vscode/tree/main/extensions/theme-defaults). The upstream MIT license notice is kept in [LICENSE](LICENSE).

Visual Studio Code is a trademark of Microsoft Corporation. This port is unofficial and is not endorsed by Microsoft.
