# Laravel8 のテンプレート

## 各種バージョン

- PHP8.1
- MySQL8.0
- nginx1.20.2

## 使い方

- リポジトリを `git clone`
- `.env.example` をコピーして `.env` を作成
- プロジェクトルートで `make install`

## 既知のエラー

- Error response from daemon: unrecognized image ID

`make install` 時に発生する場合あり。もう一度 `make install` を行う。
