# Spring Boot x PostgreSQL x Docker(Compose V2) 構築Template

## 使用方法
細かい内容は自身の以下の記事にて紹介しています。

https://qiita.com/Keichan_15/items/7ec1e8d417e273143c34

以下のコマンドを順番に入力します。

```
$ docker compose up -d

$ docker compose exec app bash

bash-4.4# sh gradlew build
```
※Buildの際に下記エラーが発生します
```
bash-4.4# sh gradlew build

xargs is not available
```
以下のコマンドを入力してください
```
bash-4.4# microdnf install findutils
```
