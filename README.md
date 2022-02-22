# Docker構築手順書

※ [app]・・・appコンテナ  
※ [db]・・・dbコンテナ  
※ [mysql]・・・mysql  


## 環境

```
MySQL 8.0  
php 8.1  
php-fpm  
nginx
```

## フォルダ構成

```
プロジェクト
  ├── README.md
  ├── infra
  │   ├── mysql
  │   │   ├── Dockerfile
  │   │   └── my.cnf
  │   ├── nginx
  │   │   └── default.conf
  │   └── php
  │       ├── Dockerfile
  │       └── php.ini
  ├── docker-compose.yml
  └── src
      └── Laravelのプロジェクト

```
