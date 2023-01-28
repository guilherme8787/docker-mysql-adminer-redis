## Docker com PHP 8 e Apache 2

Docker com mysql, adminer e redis, altere no docker-compose.yml a senha das 
aplicações pela senha que desejar, ex.: "<sua-senha-aqui>" -> "senha"

_Requisitos_

**Docker 2.3 ou superior**

Uso

```
git clone https://github.com/guilherme8787/docker-mysql-adminer-redis.git
```

```
cd docker-mysql-adminer-redis
```

```
docker-compose up -d --build
```