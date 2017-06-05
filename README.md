# Help2Save!

Um web-app para ajudar instituições de caridade, á encontrar voluntários.

### Tecnologias utilizadas:
  - Ruby 2.3.
  - Rails 5.0.2.
  - Docker/Docker-compose.

### Depêndencias:

 - [Instalando docker Community Edition ](https://docs.docker.com/engine/installation/)
 - [Instalando docker-compose](https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-16-04).

### Após instalar as depêndencias á cima, rodar os comando listados abaixo:

#### How to install:

```sh
$ docker-compose build
$ docker-compose run --rm website rake db:create db:migrate
$ docker-compose up
```
