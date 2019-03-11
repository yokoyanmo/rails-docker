## docker-compose build
Dockerイメージを構築

## docker-compose up
docker-compose.ymlで定義したサービスを起動

## docker-compose up -d
buildしてからupさせる

## docker-compose run web rake db:create
Railsで使用するデータベースを作成

## docker-compose ps
起動しているコンテナを確認

## docker-compose stop
起動しているコンテナを停止する

## docker-compose start
停止しているコンテナを起動する

## docker-compose down
コンテナを停止し削除する

## docker images
イメージの確認

## docker rmi イメージID
イメージを削除する

## docker-compose down --rmi all -v
イメージやボリュームをまとめて削除する
