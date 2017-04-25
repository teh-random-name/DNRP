<h1>DNRP<br>
<small>Docker Nginx Redis PHP7 Stack</small>
</h1>

Every container used in this stack is running [Alpine Linux](https://alpinelinux.org) which is a light-weight, security-oriented distro, this allows the resulting containers to be smaller compaired to containers using standard distros. 

Some issues do arsie from using Alpine, more info can be found on the docker container's Docker Hub page.

Connect to Redis server via `http://redis:6379`
Can also talk to php-fpm via `http://php7:9000`

Uses "offical" [PHP](https://hub.docker.com/_/php/), [Nginx](https://hub.docker.com/_/nginx/), and [Redis](https://hub.docker.com/_/redis/) containers.