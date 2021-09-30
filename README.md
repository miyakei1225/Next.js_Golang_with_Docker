# Next.js&Golang with Docker
Docker環境でNext.js&TypeScript、Golangを動かすためのレポジトリーです。

## 💻 Dependency
・Next.js ver2.6.6

・TypeScript

・Golang

## 🌊 Usage
1. コンテナイメージbuild
<p>docker-compose build</p>

2. Next.jsアプリケーション作成(TypeScript環境)
<p>docker-compose run --rm next yarn create next-app . --typescript</p>

3.コンテナ立ち上げ(バックグラウンド実行)
<p>docker-compose up -d</p>

4.コンテナ閉じる
<p>docker-compose down</p>

## 👨‍💻 Authors
Keitaro Miyano

## ✏️  Others
