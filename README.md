## docker-compose のサービス構築方法

```
docker compose build
```

## docker-compose のサービスをデーモンで立ち上げる

```
docker compose up -d
```

## Laravelプロジェクトを作成

```
docker compose run app composer create-project laravel/laravel
```

## localページの表示url

http://localhost:8000/

（Laravelプロジェクトを作成前はNot Foundが表示されます）

## dbへの接続

```
./mysql
```
