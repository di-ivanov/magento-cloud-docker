docker buildx build -t diivanov/php-mc:7.4-1.3.0-fpm --platform linux/arm64 --push ./images/php/7.4-fpm
docker buildx build -t diivanov/php-mc:7.4-1.3.0-cli --platform linux/arm64 --push ./images/php/7.4-cli
docker buildx build -t diivanov/elasticsearch-mc:7.11-1.3.0 --platform linux/arm64 --push ./images/elasticsearch/7.11
docker buildx build -t diivanov/elasticsearch-mc:7.11-1.3.0 --platform linux/arm64 --push ./images/elasticsearch/7.11
docker buildx build -t diivanov/nginx-mc:1.19-1.3.0 --platform linux/arm64 --push ./images/nginx/1.19
docker buildx build -t diivanov/varnish-mc:6.6-1.3.0 --platform linux/arm64 --push ./images/varnish/6.6
