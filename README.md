# sublime-config
Config files for sublime-text and sublime-merge

They go into `~/.config/sublime-{text|merge}/`.

# Essential plugins

- A File Icon
- Comments Aware Enter
- Emmet (for web design)
- LSP
- LSP-pylsp – convenience package for python-lsp-server, or see custom installation in [Python LSP](#python-lsp)
- LSP-rust-analyer – requires `rust-analyzer` (can be installed via rustup)
- Expand Selection to Quotes
- MarkdownPreview
- MarkdownEditing
- RustEnhanced
- SublimeLinter
- SublimeLinter-annotations – for marking TODO, WARNING, etc
- Pretty JSON – format and validate JSON files
- rainbow_csv
- DocBlockr – if using C/C++/JavaScript/PHP

## Python LSP

Either install the LSP-pylsp sublime package for convenience, or for the absolute latest version of all paackages, do this:

```bash
pip3 install --user python-lsp-server[all] python-lsp-ruff pyls-isort
```

> **NOTE**: python-lsp-black seems to be unnecessary since new versions of LSP and causes problems with duplicate black plugins

And then override `command` and `env` settings in [LSP-pylsp.sublime-settings](https://github.com/staticf0x/sublime-config/blob/master/sublime-text/Packages/User/LSP-pylsp.sublime-settings).

## Syntax definitions

- TOML
- fish
- RPM Spec Syntax
- Sass
- Dockerfile Syntax Highlighting
- INI – for tox.ini etc
- Just – for justfile
- Typst – if using [Typst](https://github.com/typst/typst)

# Theme

- Color scheme: Boxy Yesterday
- Theme: Default
