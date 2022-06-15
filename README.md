# Docker上でWordPress環境構築

## 概要
- Dockerコンテナ上にWordPressの開発環境を構築する
- 本番環境に構築されたWordPressをローカルのDocker環境に移す

---

All-in-One WP Migration のファイルアップロード制限に引っかかる場合、.htaccessに以下を記載する
```
php_value upload_max_filesize 512M
php_value post_max_size 512M
php_value max_input_time 300
php_value max_execution_time 300
```

## 参考
[サーバー上のWordPressサイトの画像や投稿データを超簡単にローカルにコピーする方法](https://yosiakatsuki.net/blog/copy-site-data-to-local/)