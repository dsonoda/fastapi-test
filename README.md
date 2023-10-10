# docs
https://zenn.dev/sh0nk/books/537bb028709ab9

# アプリ起動
docker-compose up

# アプリのAPIを叩く
http://localhost:8000/docs

# 起動中のDBにログイン
docker-compose exec db mysql demo

# アプリ停止
docker-compose stop

# test
docker-compose run --entrypoint "poetry run pytest tests --asyncio-mode=auto" demo-app
