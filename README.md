<!-- @format -->

# docker_wp_mysql_phpmyadmin

Wordpress と PHPMyAdmin が動く docker 雛形です。

## ローカルホスト

ローカルホスト WordPress
http://localhost:1010

※初回は「このページは動作していません」が出るので、ファイルの生成が終わる 2 分程度待つ。

ローカルホスト PHPMyAdmin
http://localhost:1111

## コマンド

コンテナ作成&起動

```
docker-compose up -d
```

コンテナの中に入る

```
docker-compose exec wordpressなど bash
```

コンテナ停止する

```
docker-compose stop
```

コンテナ削除する

```
docker-compose down
```

参考記事

https://qiita.com/tomokei5634/items/75d2501cfb968d0cfab5
