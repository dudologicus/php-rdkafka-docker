# Supported tags and respective `Dockerfile` links
[`latest`, `73-fpm-alpine3.10-lib-1.2.0-r0-ext-4.0.0-composer` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/73-fpm-alpine3.10-lib-1.2.0-r0-ext-4.0.0-composer/Dockerfile "Dockerfile")

[`73-fpm-alpine3.10-lib-1.2.0-r0-ext-3.1.2-composer` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/73-fpm-alpine3.10-lib-1.2.0-r0-ext-3.1.2-composer/Dockerfile "Dockerfile")

[`73-fpm-alpine3.10-lib-1.1.0-r0-ext-3.1.1-composer` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/73-fpm-alpine3.10-lib-1.1.0-r0-ext-3.1.1-composer/Dockerfile "Dockerfile")

[`72-fpm-alpine3.8-lib-1.1.0-r0-ext-3.1.1` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/73-fpm-alpine3.10-lib-1.1.0-r0-ext-3.1.1/Dockerfile "Dockerfile")

[`72-fpm-alpine3.8-lib-0.11.6-r0-ext-3.0.5-composer` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/72-fpm-alpine3.8-lib-0.11.6-r0-ext-3.0.5-composer/Dockerfile "Dockerfile")

[`72-fpm-alpine3.8-lib-0.11.6-r0-ext-3.0.5` (Dockerfile)](https://github.com/nick-zh/php-rdkafka-docker/blob/72-fpm-alpine3.8-lib-0.11.6-r0-ext-3.0.5/Dockerfile "Dockerfile")


# Build it yourself
```
docker build . --build-arg LIBRDKAFKA_VERSION=<version> --build-arg EXT_RDKAFKA_VERSION=<version> -t <tag>
```
