# Belajar Docker Compose

Membuat docker compose
```
docker compose create
```

melihat container
```
docker compose ps
```

menjalankan container
```
docker compose start
```

menghentikan container
```
docker compose stop
```

menghapus container
```
docker compose down
```

melihat semua project yang sedang berjalan
```
docker compose ls
```

memantau docker event

```
docker events --filter ‘container=nama’
```

build dockerfile
```
docker compose build
```

extend service (berguna untuk ganti mode konfigurasi: dev, prod, local)
```
docker compose -f docker-compose.yaml -f prod.yaml create
```

```
docker compose -f docker-compose.yaml -f dev.yaml create
```

```
docker compose -f docker-compose.yaml -f dev.yaml create
```