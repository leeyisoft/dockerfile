
# php kafka
```
docker build -f php72_kafka_redis_mysql_Dockerfile -t php72-kafka-redis-mysql:1.0 .
docker build -f php74_kafka_redis_mysql_Dockerfile -t php74-kafka-redis-mysql:1.0 .

docker build -f php74_kafka_redis_mysql_swoole_Dockerfile -t php74-kafka-redis-mysql-swoole:1.0 .

docker build -f php74_rabbitmq_redis_mysql_swoole_Dockerfile -t php74-rabbitmq-redis-mysql-swoole:1.0 .

docker build -f test_locust_wrk2_tsung_Dockerfile . -t test:v1.0
```

php 扩展版本 https://pecl.php.net/packages.php
