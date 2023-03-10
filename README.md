# Deploy Wordpress on Localhost and in Production using Docker Compose

You can automatically deploy a local docker wordpress site in 5 minutes
using the following commands:

``` bash
# Download a wordpress docker-compose example
git https://github.com/AlirezaBabaeii/Wordpress-docker-compose.git
cd wordpress-docker-compose
# Build and start installation
docker-compose up -d
```

Visit your site at <http://localhost> and your database via phpMyAdmin
at <http://localhost:8080>.

Default identification for your wordpress website admin:

  - `Username: wordpress` and
  - `Password: wordpress`

Default identification for the phpMyAdmin interface:

  - `Username: root` and
  - `Password: password`

**Useful set of commands to know**:

``` bash
# Stop and remove containers
docker-compose down
# Build, and start the wordpress website
docker-compose up -d --build
# Reset everything
docker-compose down
```

## References

  - [WordPress: with Nginx web server in
    Docker](https://github.com/mjstealey/wordpress-nginx-docker)
  - [Quickstart: Compose and
    WordPress](https://docs.docker.com/compose/wordpress/)
