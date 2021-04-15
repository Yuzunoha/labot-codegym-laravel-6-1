## 教科書

- [速習 Laravel 6 速習シリーズ Kindle 版](https://www.amazon.co.jp/dp/b07xc2ql4m)

## はじめに

- [notion の案内](https://www.notion.so/codegym/Laravel-5158254eedd9481baea7cde3ab6585dd)をご確認ください

## 初回セットアップ手順

1. 下記のコマンドを実行する

   ```
   make init
   ```

   - PC の性能にもよるが時間が掛かる

   - ライブラリ提供元の変更によってログに warning や error が入ることがあるが、`make init` 自体が成功すれば問題ない

1. 起動した laravel アプリをブラウザで表示する

   - http://localhost:10680 にアクセスする

1. 起動した phpMyAdmin をブラウザで表示する

   - http://localhost:10681 にアクセスする

## コンテナを起動する方法

- 下記のコマンドを実行する

  ```
  make up
  ```
