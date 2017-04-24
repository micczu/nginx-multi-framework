# nginx-multi-framework
(sandbox)

Simple try of making docker-compose file to create nginx with different framework backends.

- php7-fpm
- php5.6-fpm
- nodejs

# Usage:
    git clone https://github.com/micczu/nginx-multi-framework
    cd nginx-multi-framework
    docker-compose up -d

For testing add server IP with domain and subdomains to hosts file:

    <serverIP>    docker.local php7.docker.local php56.docker.local nodejs.docker.local pma.docker.local


# ToDo:
docker.local domain still not work


Workspace forked from https://github.com/laradock/workspace
