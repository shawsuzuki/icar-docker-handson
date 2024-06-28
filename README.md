# ICAR_docker_handson

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

icarの新人向けdocker講義用

## 実行用（？）コマンド

### イメージを作成

$ docker compose build --no-cache  

### イメージからコンテナを作成

$ docker compose up -d

### コンテナに入る

$ docker exec -it ${container_name} /bin/bash

## 確認用（？）コマンド

### イメージ一覧を取得（`-a`をつけると、stopしているimageも表示）  

$ docker images

### コンテナ一覧を取得（`-a`をつけると、stopしているimageも表示）  

$ docker ps

### dockerネットワーク一覧を取得（`-a`をつけると、stopしているimageも表示）  

$ docker network ls  
