# Resume-Website

## 🌱 概要

レジュメとポートフォリオを紹介する静的なウェブサイト

## 🏠 URL

[https://resume-website.teradad41.com](https://resume-website.teradad41.com)

## 📝 説明

AWSのEC2 Ubuntuサーバインスタンスを利用して、ウェブサイトの開発・デプロイをしました。

NGINXを用いてサーバを構成し、ウェブサイトのコンテンツを提供する設定を行い、UFWを活用してサーバーのファイアウォール設定を管理しました。これにより、HTTP、HTTPS、SSHトラフィックのためのポートを開放しました。

ウェブサイトのドメインはEC2サーバのIPアドレスを指すように設定し、DNS設定はドメインレジストラを通じて行いました。

セキュリティ面では、Let's EncryptとCertbotから取得した証明書を使用して、サイトへの全接続を暗号化・認証し、ユーザーデータの完全性を保護するためにHTTPSを導入しました。

## 💾 使用技術

- フロントエンド：HTML, CSS, JavaScript
- 本番環境：AWS EC2（Ubuntu）
- Web サーバー：Nginx
- 開発環境：Ubuntu
- その他：Certbot

## 📜 作成の経緯

- 本番環境の Webサーバー環境の構築
- AWS EC2 インスタンスを使用して、クラウドのエコシステムを理解する
- SSH シェルと Git ソース管理ツールを使ってサーバを管理する
- DNS について学び、独自のドメイン・サブドメインを設定する
- TLS による安全な暗号化について学び、独自の証明書を作成して HTTP セキュアを設定する

## 💻 学んだこと

- クライアント・サーバアーキテクチャ
- HTTP プロトコルを用いたリクエスト・レスポンス
- 本番環境とは何か
- 本番環境への SSH 接続の方法
- Nginx の設定ファイルの変更の仕方

## 📑 参考

- [Nginx](https://www.nginx.co.jp)
- [Certbot](https://certbot.eff.org)
- [Let's Encrypt](https://letsencrypt.org/ja/)
