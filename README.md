# lamp-on-docker
## About
今までVagrantでローカルの開発環境を構築していましたが、Dockerの方が早いし複雑な構成にも出来るし、何よりデプロイが簡単ということでDocker始めました。
このスクリプトはdockerとdocker-composeさえ入っていれば、
```
git clone https://github.com/LeoIsaac/lamp-on-docker.git
cd lamp-on-docker
docker-compose up -d
```
ってやるだけで```/html```の中身がlocalhost:80で見れます。

## Structure
* Webコンテナ
    - ubuntu:latest
    - Apache, PHP
* MySQLコンテナ
    - mysql:latest
