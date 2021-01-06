# docker-laravel-vue-handson

## 参考サイト
https://qiita.com/shimotaroo/items/29f7878b01ee4b99b951

## URL
http://localhost:8000/

## クローン後

#### ビルド
```
docker-compose up -d --build
```

#### コンテナに入る
```
docker-compose exec app bash
```

#### Conposerをインストール
```
composer install
```

#### .envを作る
```
cp .env.example .env
```

#### アプリケーションキーを作成
```
php artisan key:generate
```

#### マイグレート
```
php artisan migrate
```