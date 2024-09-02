# Laravel & WebServer & DB & Docker (& Google Cloud Run)

## Plan

(こちら)[https://www.twilio.com/ja-jp/blog/get-started-docker-laravel-jp]を参考に、
段階を踏んで1つづつ実装。

1. 新規ディレクトリ作成
2. 適宜Dockerfile, docker-compose.ymlを作成・配置
3. 準備が整ったらコンテナのビルド `docker compose up -d --build`
4. Laravelアプリのセットアップ
5. 適宜コンテナの中（Web, DBそれぞれ別のターミナルで）に入って確認及びphp artisan, composeコマンド等実行
6. アプリケーションの構築または機能追加・改修
7. (テスト)
8. (スケーリング)
9. (Google Cloud Runにコンテナの形でデプロイ）

※7番以降はオプションだが、どこかにデプロイは必須。Dockerコンテナでなくてもいい。またNetlifyとか？
