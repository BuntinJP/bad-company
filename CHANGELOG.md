# Change Log

This is Bad Company. A VSCode Extension Pack for me.

## [Unreleased]

## [2.1.5] 2026/02/25
### Changed
- `AGENTS.md` に CHANGELOG の実行主体記載ルールを追加 `(Updated by Codex)`

## [2.1.4] 2026/02/25
### Added
- `AGENTS.md` を追加し、AIエージェント向けの運用ルールを明文化

### Changed
- GitHub Actions `publish.yml` の Bun バージョンを `1.3.9` に固定
- CIの依存インストールを `bun install --frozen-lockfile` に変更
- Publish workflow に `concurrency` を追加し、同時実行競合を防止

## [2.1.3] 2026/01/25
### Added
- `esbenp.prettier-vscode` (Added by Jules)

## [2.1.2] 2026/01/25
### Removed
- `ms-azuretools.vscode-docker`

## [2.1.1] 2026/01/25
### Added
- `openai.chatgpt`

## [2.1.0] 2026/01/25
### Added
- `editorconfig.editorconfig`
- `ms-azuretools.vscode-docker`
- `unifiedjs.vscode-mdx`
- `tailscale.vscode-tailscale`

## [2.0.0] 2025/06/27

- AI開発ツールに焦点を当てた拡張機能パックの完全刷新
- コーディング生産性向上のためのモダンなAI拡張機能を追加
- 非推奨および古い拡張機能を削除
- 現在の開発ワークフローに最適化されたコレクションに整理

## [1.1.0] 2024/03/11
### Added
- `oven.bun-vscode`
- `shakram02.bash-beautify`
- `ms-dotnettools.csharp`
- `ms-dotnettools.csdevkit`
- `mhutchie.git-graph`
- `ms-vscode.cpptools-extension-pack`
- `streetsidesoftware.code-spell-checker`
- `tamasfe.even-better-toml`
- `GitHub.copilot-chat`
- `christian-kohler.npm-intellisense`
- `mosapride.zenkaku`
- `ms-python.autopep8`

### Removed
- `alexdima.copy-relative-path`
- `christian-kohler.path-intellisense`
- `dbaeumer.vscode-eslint`
- `EliverLara.andromeda`
- `formulahendry.code-runner`
- `helgardrichard.helium-icon-theme`
- `mohsen1.prettify-json`
- `MS-CEINTL.vscode-language-pack-ja`
- `ms-python.isort`
- `redhat.java`
- `shiro.basicpack`
- `usernamehw.errorlens`
- `wayou.vscode-todo-highlight`
- `xabikos.JavaScriptSnippets`
- `golang.go`
- `rust-lang.rust-analyzer`
- And other legacy extensions...

## [0.0.1] 2023/02/27
- Initial release
