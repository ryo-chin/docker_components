This is a repository that keeps frequently used DockerImages together.

# Basic
```shell
# Create containers and start it.
#   -d: execute background
docker-compose up -d

# Stop service
docker-compose stop
# Start service
docker-compose start

# Delete service
docker-compose down
```

# Images
## mysql
```shell
# connect mysql
docker exec -it hakiba-mysql mysql -u hakiba_user -D hakiba_db -p
```
