# WordPress環境

- php7.3
- WordPress5.4
- apache

# 起動

## 初回のみ

```
docker-compose up -d --build
```
## 2回目以降
```
docker-compose up -d
```

# 停止
```
docker-compose down
```

# アクセス

## site
http://localhost/

## phpMyAdmin
http://localhost:8080/
