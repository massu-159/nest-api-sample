# next-nest-api-todo-sample

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

Nest.jsでapi作成。

フロントは、[next-nest-front-todo-sample](https://github.com/massu-159/next-nest-front-todo-sample)

ORMに[prisma](https://www.prisma.io/)を使用

DBにはPostgresQLを使用（DockerでDB構築）

[Postman](https://www.postman.com/) でapiテスト

jwt、surf、...

url はこちら
https://github.com/massu-159/next-nest-api-todo-sample


## インストール

```bash
$ npm install
```

## アプリケーション実行

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Docker環境構築
```
docker compose up -d
```

## 1. アプリケーションの仕様

### 仕様

- Todoリスト
  - Todo一覧表示
  - Todo作成処理
  - Todo更新処理
  - Todo削除処理
- 認証
  - ユーザー登録
  - ログイン　
  - ログアウト
