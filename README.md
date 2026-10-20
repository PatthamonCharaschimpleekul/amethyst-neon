# Amethyst Neon

A custom dark VS Code theme — blue-to-black gradient, built around one rule: **one code category, one hue**. Nothing shares a color with something it isn't.

Born from long eye-testing sessions, tuned for readability (every token color passes a ≥ 4.0 contrast gate against the editor background).

## Palette

| Category | Color | | Category | Color |
|---|---|---|---|---|
| variable | `#3AFCE2` cyan | | string | `#8FF247` green |
| parameter | `#FFB340` amber | | number | `#7DCCFF` blue |
| function | `#E4FA7E` lime | | constant | `#FFA8D0` pink |
| class / module | `#FF9DCA` **bold** rose | | property | `#8CF0D8` seafoam |
| keyword (`if`, `for`) | `#E5B1FF` lavender | | decorator | `#FF93A9` coral |
| operator (`=`, `+`) | `#FFA3A3` light red | | comment | `#A9B4C7` *italic* grey |

Background is a 6-zone ramp from darkest to lightest: title bar `#0D0A22` → status bar `#110F2B` → activity bar `#141533` → panel/terminal `#181B3E` → sidebar/tabs `#1C2348` → editor `#23355C`.

## Install (from source, no toolchain)

1. Clone or [download this repo as ZIP](https://github.com/PatthamonCharaschimpleekul/amethyst-neon/archive/refs/heads/main.zip)
2. Copy the whole folder into your extensions directory, renamed:
   - Windows: `%USERPROFILE%\.vscode\extensions\saimai.amethyst-neon-0.1.0`
   - macOS/Linux: `~/.vscode/extensions/saimai.amethyst-neon-0.1.0`
3. In VS Code: `F1 → Developer: Reload Window`
4. `Ctrl+K Ctrl+T` → pick **Amethyst Neon**

(If you have Node.js, you can also package it as a `.vsix` with `npx @vscode/vsce package` and install via *Install from VSIX…*)

## Requirements

VS Code ≥ 1.75. Semantic highlighting works best with Pylance / any LSP that emits semantic tokens.

## License

MIT — use it, fork it, tweak the colors freely.
