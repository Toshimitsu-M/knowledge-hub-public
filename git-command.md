### ツリー状で確認する。
git log --oneline --graph --all --decorate

### ブランチ一覧の表示
git branch

### ブランチ命名規約
| 用途       | 例                              | 意味                   |
| -------- | ------------------------------ | -------------------- |
| 新機能追加    | `feature/add-user-api`         | ユーザーAPIを追加           |
| バグ修正     | `fix/incorrect-login`          | ログイン不具合の修正           |
| リファクタリング | `refactor/user-service`        | サービス層の整理             |
| 実験・検証    | `experiment/openapi-generator` | OpenAPI Generatorの検証 |
| リリース準備   | `release/v1.2.0`               | バージョン1.2.0リリース       |


### ブランチの追加（切り替え含む）
git checkout -b feature/add-user-api

### ブランチの削除
git checkout -d feature/add-user-api

| よく使うコマンド                | 意味            |
| ----------------------- | ------------- |
| `git remote -v`         | 現在のリモート設定を確認  |
| `git pull`              | 最新の変更を取得      |
| `git push`              | 自分の変更をリモートに送信 |
| `git branch -a`         | ブランチ一覧を確認     |
| `git checkout <branch>` | ブランチを切り替え     |


### 
###
###
