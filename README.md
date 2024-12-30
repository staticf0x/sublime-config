# sublime-config

Config files for sublime-text and sublime-merge

They go into `~/.config/sublime-{text|merge}/`.

# Essential plugins

- A File Icon
- Color Highlighter
- Comments Aware Enter
- EditorConfig
- Emmet (for web design)
- Expand Selection to Quotes
- LSP
- LSP-pylsp – convenience package for python-lsp-server, or see custom installation in [Python LSP](#python-lsp)
- LSP-rust-analyer – requires `rust-analyzer` (can be installed via rustup)
- LSP-json
- MarkdownPreview
- MarkdownEditing
- RustEnhanced
- SublimeLinter
- SublimeLinter-annotations – for marking TODO, WARNING, etc
- Path Tools
- Pretty JSON – format and validate JSON files
- rainbow_csv
- DocBlockr – if using C/C++/JavaScript/PHP

## Python LSP

Either install the LSP-pylsp sublime package for convenience, or for the absolute latest version of all packages, do this:

```bash
pip3 install --user python-lsp-server[all] python-lsp-ruff pyls-isort
```

> **NOTE**: python-lsp-black seems to be unnecessary since new versions of LSP and causes problems with duplicate black plugins

And then override `command` and `env` settings in [LSP-pylsp.sublime-settings](https://github.com/staticf0x/sublime-config/blob/master/sublime-text/Packages/User/LSP-pylsp.sublime-settings).

## Syntax definitions

- Dockerfile Syntax Highlighting
- fish
- GraphQL
- INI – for tox.ini etc
- Just – for justfile
- RPM Spec Syntax
- Sass
- TOML
- Typst – if using [Typst](https://github.com/typst/typst)

# Theme

- Color scheme: Boxy Yesterday
- Theme: Default
