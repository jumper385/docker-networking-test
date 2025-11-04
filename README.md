# Docker Compose Networking Test

Configures two hosts on two subnets; each of which are presistent docker images

To run the demo, runt the following command to build the container
```
docker compose up --build -d
```

To use the host bash, run the following:
```
docker compose exec <container_name> bash
```

valid `contianer_name` is either `ubuntu` or `test_host`
