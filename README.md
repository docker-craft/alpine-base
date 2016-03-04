alpine-base
=============

A base image to run anything. It's based in alpine 3.3, adding basic software bash openssl and curl.

## Build

```
docker build -t rawmind/alpine-base:<version> .
```

## Versions

- `0.3.3` [(Dockerfile)](https://github.com/rawmind0/alpine-base/blob/master/Dockerfile).

## Usage

To use this image include `FROM rawmind/alpine-base` at the top of your `Dockerfile`.
