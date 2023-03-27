# 🐳 Docker + PHP 8:Latest + MySQL + Apache Symfony 6:Latest + Npm

## Description

This is a complete stack for running Symfony 6 into Docker containers using docker-compose.

It is composed by 3 containers.

## Installation

1. 😀 Clone this rep.
2. Run `make start` to build containers.
3. Inside the `php` container, run `make bash` to initialize project from `/var/www` folder.
4. And use composer to create project:

```shell
composer create-project symfony/skeleton:"6.3.*" project
cd project
composer require webapp
```