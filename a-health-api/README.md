# A. ヘルスチェックAPI

シンプルなヘルスチェックエンドポイントを実装したRails APIサーバー

## 技術スタック

- Ruby 4.0
- Rails 8.1 (APIモード)
- RSpec

## セットアップ

VSCodeかCusorでこのプロジェクトを開き、「Reopen in Container」を選択するとdevcontainerが起動します。
依存関係のインストールは`postCreateCommand`で自動実行されます。

## APIエンドポイント

| メソッド | パス      | 説明           |
| -------- | --------- | -------------- |
| GET      | `/health` | ヘルスチェック |

### レスポンス例

```json
{ "status": "ok" }
```

## テスト

```bash
bundle exec rspec
```
