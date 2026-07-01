# json-lsp

JSON/JSONC language server (**[vscode-json-languageserver](https://www.npmjs.com/package/vscode-json-languageserver)**) for Claude Code, providing code intelligence, diagnostics, and completion.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![JSON](https://img.shields.io/badge/JSON-008080?logo=json&logoColor=white)](https://www.json.org/)
[![JSONC](https://img.shields.io/badge/JSONC-008080)](https://code.visualstudio.com/docs/languages/json#_json-with-comments)
[![Claude Plugin](https://img.shields.io/badge/Claude-Plugin-D97757?logo=claude&logoColor=white)](https://docs.claude.com/en/docs/claude-code)
[![Marketplace](https://img.shields.io/badge/Marketplace-lsp--marketplace-8250DF)](https://github.com/taehun-kmu/lsp-marketplace)

## Supported Extensions

`.json`, `.jsonc`

## Installation

### Via bun (recommended)

```bash
bun add -g vscode-json-languageserver
```

### Via pnpm

```bash
pnpm add -g vscode-json-languageserver
```

### Via npm

```bash
npm install -g vscode-json-languageserver
```

- Ensure [`vscode-json-languageserver`](https://www.npmjs.com/package/vscode-json-languageserver) is on your `PATH` so Claude Code can launch it.
- Verify with `command -v vscode-json-languageserver`.

## More Information

- [vscode-json-languageserver on npm](https://www.npmjs.com/package/vscode-json-languageserver)
- [VS Code JSON Language Features](https://github.com/microsoft/vscode/tree/main/extensions/json-language-features/server)
