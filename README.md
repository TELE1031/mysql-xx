# mysql-cn

## How to use devcontainer


Start the container

```

docker run --name mysql-demo -e MYSQL_ROOT_PASSWORD=root -d  -v $(pwd):/test mysql:8.0.30

```
