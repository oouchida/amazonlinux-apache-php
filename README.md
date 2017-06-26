amazonlinux-apache-php
====

Dockerを使い、Amazon Linux+Apache+phpで環境を構築しています

## Description
本イメージは、PHPフレームワークでアプリケーションを作る土台となっています。

## Usage
git clone https://github.com/oouchida/amazonlinux-apache-php.git  
cd amazonlinux-apache-php  
docker build -t oouchida/amazonlinux-apache-php .  
docker container run -itd -p 80:80 oouchida/amazonlinux-apache-php

## Test
ブラウザでhttp://localhost にアクセスしてください。
