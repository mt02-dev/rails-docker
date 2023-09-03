# README

* 環境
  Ruby: 3.2.2   
  postgres: 12   
* 環境構築方法

  * 作業ディレクトリの作成
  ```sh
  git clone https://github.com/mt02-dev/rails-docker.git
  ```
  * コンテナの起動   
  以下のコマンドで、バックグラウンドで起動します。
  ```
  docker compose up --build -d
  ```
  * Webアプリの動作確認   
  ブラウザで以下のURL記述欄に貼り付けてEnter
  ```
  localhost:3000
  ```
  以下の画像が出ればOK   
  ![rails_app](https://github.com/mt02-dev/rails-docker/assets/81817850/35cbd7f8-ad52-4f7a-9f90-29e462503893)

