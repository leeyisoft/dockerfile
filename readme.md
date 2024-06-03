
# php kafka
```
docker build -f php72_kafka_redis_mysql_Dockerfile -t php72-kafka-redis-mysql:1.0 .
docker build -f php74_kafka_redis_mysql_Dockerfile -t php74-kafka-redis-mysql:1.0 .

docker build -f php74_kafka_redis_mysql_swoole_Dockerfile -t php74-kafka-redis-mysql-swoole:1.0 .

docker build -f php74_rabbitmq_redis_mysql_swoole_Dockerfile -t php74-rabbitmq-redis-mysql-swoole:1.0 .


docker build -f test_locust_wrk2_tsung_Dockerfile . -t test:v1.0
```

php 扩展版本 https://pecl.php.net/packages.php



## php74_rabbitmq_redis_mysql_swoole_Dockerfile
```
docker build -f php74_rabbitmq_redis_mysql_swoole_Dockerfile -t php74-rabbitmq-redis-mysql-swoole:1.3 .
docker login
docker tag php74-rabbitmq-redis-mysql-swoole:1.3 leeyi/php74-rabbitmq-redis-mysql-swoole:1.3
docker push leeyi/php74-rabbitmq-redis-mysql-swoole:1.3
```

##
```
docker build -f ./rabbitmq3_Dockerfile -t rabbitmq3:1.3 .
docker login
docker tag rabbitmq3:1.3 leeyi/rabbitmq3:1.3
docker push leeyi/rabbitmq3:1.3
```
