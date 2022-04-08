# Tchap Sydent

This repo only hosts Github Action CI to build the docker image from the [main sydent repo](https://github.com/matrix-org/sydent/tree/dinsic).

## Pull this image

```
docker login ghcr.io --username <github_username> --password-stdin
docker pull ghcr.io/tchapgouv/tchap-sydent:latest
```

## Create new release

- Create a new tag, in semantic versionning format `vX.X.X`

It will pull matrix-sydent/dinsic and create a new docker image.