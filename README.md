# docker-python-app
docker+flask
https-portalでssl対応

## コマンド
### コンテナ起動
docker compose -f 'docker-compose.yml' up -d --build
### コンテナ終了
docker compose -f 'docker-compose.yml' down
### コンテナに入る
docker exec -it python bash

