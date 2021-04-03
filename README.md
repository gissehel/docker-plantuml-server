# docker-plantuml-server

[plantuml-server](https://github.com/plantuml/plantuml-server) in Docker.

* Project page: https://github.com/gissehel/docker-plantuml-server
* Docker hub page : https://hub.docker.com/r/gissehel/docker-plantuml-server
* GHCR page : https://github.com/users/gissehel/packages/container/package/plantuml-server

## Usage

```sh
# either run in foreground (ctrl-c exits the server)
docker run -it -p 8080:8080 --rm ghcr.io/gissehel/plantuml-server

# or in background (server keeps running until specifically killed)
docker logs -f $(docker run -d -p 8080:8080 ghcr.io/gissehel/plantuml-server)
```

Visit http://ip-of-your-docker-host:8080 in your browser
