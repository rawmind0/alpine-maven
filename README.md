[![](https://images.microbadger.com/badges/image/rawmind/alpine-maven.svg)](https://microbadger.com/images/rawmind/alpine-maven "Get your own image badge on microbadger.com")

alpine-maven
=============

This image is the [maven][maven] base. It comes from [alpine-jdk8][alpine-jdk8].

## Build

```
docker build -t rawmind/alpine-maven:<version> .
```

## Versions

- `3.3.9-1` [(Dockerfile)](https://github.com/rawmind0/alpine-maven/blob/3.3.9-1/Dockerfile)


## Usage

To use this image include `FROM rawmind/alpine-maven` at the top of your `Dockerfile`, and add the entrypoint to compile, test, release.... your app.

[alpine-jdk8]: https://github.com/rawmind0/alpine-jdk8/
[maven]: https://maven.apache.org