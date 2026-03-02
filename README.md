# EASY RUBY ON RAILS TUTORIAL

やさしめなRuby on Railsのチュートリアルです。

## セットアップ

### 必要なもの

- [Docker](https://www.docker.com/)
- [VS Code](https://code.visualstudio.com/) + [Dev Containers拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  - またはCursorでも可

### 手順

各チュートリアルはディレクトリごとにDev Containerで環境が用意されています。

1. やりたいチュートリアルのディレクトリをVS Codeで開く
2. コマンドパレット（`Cmd + Shift + P`）から「`Dev Containers: Reopen in Container`（コンテナーで再度開く）」を実行
3. コンテナが立ち上がったら、ターミナルでサーバーを起動

```bash
bin/dev
```

`http://localhost:3000` でアクセスできます。

## チュートリアル

### A. ヘルスチェック API

ヘルスチェックのAPIだけがあるシンプルなサーバー。APIの基本的な設定方法が理解できる。
