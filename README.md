# empty-dev-container

```sh
cd .devcontainer/
docker build -t mozyy/dev-container:1.0.6 --build-arg ANGULAR_CLI_VERSION=13.3.2 \
--build-arg HTTP_PROXY=$http_proxy --build-arg HTTPS_PROXY=$http_proxy
```