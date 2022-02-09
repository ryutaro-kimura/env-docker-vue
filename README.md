## 環境
- vue-cli 最新版
- npm
## Docker構築&起動
```
docker-compose up -d
```

## vue 実行
```
// コンテナに入る
docker-compose exec web sh

// 更新の場合
npm update

// npm 実行
npm run dev
```
