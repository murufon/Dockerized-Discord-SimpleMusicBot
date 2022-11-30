# set up

各種設定をする
公式ドキュメント参照
```
cp .env.sample .env
cp config.json.sample config.json
```

立ち上げ
```
docker compose run --rm bot npm install
docker compose run --rm bot npm run build
docker compose up -d
```
