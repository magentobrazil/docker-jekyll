# Jekyll Builder

A container run from this Docker image will build a jekyll static site. A volume is expected to be mounted to `/src` at runtime; otherwise, the container will not run correctly.

## Run example

```
docker run --rm \
  -v <vbox-share-src>:/src \
  esepublic/docker-jekyll:latest
```

A command may optionally be passed to override the default runtime command.
