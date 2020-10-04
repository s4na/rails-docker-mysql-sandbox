# Rails Docker MySQL Sandbox

[【Rails】Rails 6.0 x Docker x MySQLで環境構築](https://qiita.com/nsy_13/items/9fbc929f173984c30b5d) を参考にMySQLとRailsを一緒に動かす方法を学ぶ

```
docker-compose run web rails new . --force --no-deps --database=mysql --skip-test --webpacker
docker-compose build
docker-compose run web bundle exec rails db:create
dc run web yarn install --check-files
docker-compose up
```
