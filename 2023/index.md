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
- herokuへのデプロイ
  - git push heroku cart_checkout:main
