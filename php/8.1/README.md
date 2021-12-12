# PHP 8.1 / CLI, FPM and Swoole container images

Ubuntu 20.04 PHP 8.01 CLI and FPM container images. Packages are provided by [Ondřej Surý](https://deb.sury.org/).

Far smaller in size than PHP's official container. No need to compile any extensions: simply run `apt-get install php8.1-EXTENSION_NAME` as part of your Dockerfile

*Note on logging:* configure your application to stream logs into `php://stdout`. That's it.

