# prototype
PHPを用いた試作品です。故郷の鹿児島の観光をテーマに作成してみました。
##開発環境
php 5.6.29
MySQL 5.1.73
###signup.php
新規ユーザー登録を行います。ユーザー名とパスワードを入力して、パスワードはpassword_hash()を用いてパスワードハッシュを作成してDBのuserテーブルに挿入してます。
###login.php
signup.phpで作成したパスワードハッシュとユーザーが入力したパスワードをpassword_verify()を用いて認証する。
###作品掲載
http://210-140-96-142.jp-east.compute.idcfcloud.com/php/bin/login.php
