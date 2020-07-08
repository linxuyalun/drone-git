# drone-git

Drone plugin to clone `git` repositories by ssh

Befor using this plugin, you must fill in some contents

## Fields need to fill in

Replace all your fields formatted as `$${FIELD_NAME}` with your own values in `posix/clone`, `posix/clone-commit`, `posix/clone-pull-request` and `posix/clone-tag`.

## Build

Build the Docker image with the following commands:

```
docker build --network=host --rm -f docker/Dockerfile.linux.amd64 -t drone/git .
```
