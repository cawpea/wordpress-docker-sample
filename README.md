# WordPress + Docker の環境構築サンプル

Docker を使って、ローカル環境に WordPress を構築するサンプル

## 起動

```sh
# 環境を立ち上げ
$ docker-compose up

# 環境をシャットダウン
$ docker-compose down
```

- https://localhost:8000 でページが表示されます。
- https://localhost:8000/wp-admin で管理者ページにアクセスできます。

# 参考

- [Docker で WordPress の開発環境を作成する（M1 Mac）](https://zenn.dev/toono_f/articles/af9c62f124b44a)
