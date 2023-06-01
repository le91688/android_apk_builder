# Dockerized Android APK builder

Quickly and easily build Android APKs from docker

Contains Gradle and Android SDK

## Usage

```sh
docker run --rm -it -v $PWD:/app/ -w /app le91688/android_apk_builder gradle build
```

## Versioning

Currently this image uses Gradle 6.5 and SDK 33, but hopefully more to come. Feel free to make a PR!

## Dockerhub

https://hub.docker.com/r/le91688/android_apk_builder
