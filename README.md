# empty-dev-container

```sh
cd .devcontainer/
docker build -t mozyy/dev-container:1.0.9 --build-arg ANGULAR_CLI_VERSION=14.0.1 \
--build-arg HTTP_PROXY=$http_proxy --build-arg HTTPS_PROXY=$http_proxy
```