# docker-python-app
docker環境でpythonとflaskを学習する

## コマンド
### コンテナ起動
docker compose -f 'docker-compose.yml' up -d --build
### コンテナ終了
docker compose -f 'docker-compose.yml' down
### コンテナに入る
docker exec -it python bash

