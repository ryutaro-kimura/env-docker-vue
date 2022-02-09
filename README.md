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

// vueのプロジェクト作成
vue create hogehoge

// サーバー立ち上げ
cd hogehoge
npm run serve
```
