## 開発コンテナ（DevContainer）の使い方

このプロジェクトは [DevContainer](https://code.visualstudio.com/docs/devcontainers/containers) に対応しています。

### 必要条件
- Docker（ColimaなどでもOK）
- VSCode + [Dev Containers拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### 起動手順

1. VSCode でこのプロジェクトフォルダを開く
2. コマンドパレット（⌘+Shift+P）から `Dev Containers: Reopen in Container` を実行

これで Node.js 環境と zsh の開発環境が自動でセットアップされます。
