# Database Initialization Process

## Prerequisites
 * Docker
 * redis



## Steps
1. use container service to manage databases(create, host and destroy)
2. write compose file to setup database (docker-compose.yml)
3. execute docker and docker-compose command
4. connect to database use command line or GUI tool
5. check .env file to setup environment variables


## Scripts

``` bash
# access redis database host in docker via terminal
docker exec -it local_redisdb_dev sh

# access redis database host in docker via redis-cli
docker exec -it local_redisdb_dev redis-cli

```

## References
1. [redis admin tool](https://marcus116.blogspot.com/2020/04/tool-redis-another-redis-desktop-manager.html)
2. [redis admin tool github](https://github.com/qishibo/AnotherRedisDesktopManager/)
3. [set up password through cmd](https://webapplicationconsultant.com/docker/how-to-set-the-password-for-redis-in-docker-for-development/)