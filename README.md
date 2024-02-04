## 参考ページ
https://pontaro.net/1305/


## 次にこれを作る
https://qiita.com/katsuomi/items/d1e6625ae9a5b663e11f
https://github.com/katsuomi/Tsubuyakitter-backend/blob/master/controllers/post_controller.go

## docker
docker compose build
docker compose up
```
docker compose exec app sh
go run main.go
```
```
cd seeds
go run seeder.go
```

## 今回のアプリケーションのフォルダ構成は以下です。
```
└── app
    ├── controllers
    │   └── memoController.go
    ├── models
    │   └── memo.go
    ├── requests
    │   └── memoRequests.go
    ├── seeds
    │   └── seeder.go
    ├── go.mod
    ├── go.sum
    └── main.go
├── docker
│   └── app
│       └── Dockerfile
├── docker-compose.yml
```
