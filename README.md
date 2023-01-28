# docker-compose

> A repo to store docker config file, just use docker-compose to start it.

## Install docker-compose

### APT

```shell
sudo apt install docker-compose
```

### Pacman

```shell
sudo pacman -S docker-compose
```

## start docker container

> The example that was used in the following is `mysql.yml`.

### start service(Create container)

```shell
docker-compose -f mysql.yml up
```

### start container(The container should be created once)

```shell
docker-compose -f mysql.yml start
```

### stop container

```shell
docker-compose -f mysql.yml stop
```
