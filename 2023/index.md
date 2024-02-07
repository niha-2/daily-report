# MEMO

## wsl2

- dockerのpostgresql操作
  - psql -h localhost -p 5430 -U root
- WSL上で下記コマンドを実行。
  - ```sudo hwclock --hctosys```

## heroku

- herokuのDBクリア
  - heroku pg:reset
  - heroku run rails db:migrate
  - heroku run rails db:seed
- herokuアプリ作成
  - https://devcenter.heroku.com/ja/articles/getting-started-with-rails7#create-a-heroku-app
- herokuへのデプロイ
  - git push heroku cart_checkout:main

## rails

```
$ docker-compose run web bundle exec rake db:drop
$ docker-compose run web bundle exec rake db:create
$ docker-compose run web bundle exec rake db:migrate
$ docker-compose run web bundle exec rake db:seed
```
