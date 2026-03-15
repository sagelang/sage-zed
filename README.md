# Sage for Zed

Zed extension for the [Sage programming language](https://github.com/sagelang/sage).

## Features

- Syntax highlighting (tree-sitter based)
- Real-time error diagnostics via LSP
- Auto-indentation

## Installation

Install from the Zed extension registry:
1. Open Zed
2. Press `Cmd+Shift+X` to open Extensions
3. Search for "Sage"
4. Click Install

## Requirements

The `sage` CLI must be installed and available in your PATH:

```bash
# Homebrew
brew install sagelang/sage/sage

# Cargo
cargo install sage-lang
```

## License

MIT
