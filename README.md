# お問い合わせフォーム

## 環境構築
- Dockerビルド
- 1.git clone git@github.com:Naganuma-Mai/confirm-test.git
- 2.docker-compose up -d --build
- *MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせてdocker-compose.ymlファイルを編集してください。
- Laravel環境構築
- 1.docker-compose exec php bash
- 2.composer install
- 3.env.exampleファイルから.envを作成し、環境変数を変更
- 4.php artisan key:generate
- 5.php artisan migrate
- 6.php artisan db:seed

## 使用技術
- PHP 8.3.2
- Laravel 8.83.8
- MYSQL 10.3.39-MariaDB

## ER図
![er](https://github.com/Naganuma-Mai/confirm-test/assets/154653570/6d1eb3cd-8a34-48c4-aa81-e34b2a70b343)

## URL
- 開発環境：http://localhost/
- phpMyAdmin:http://localhost:8080/
