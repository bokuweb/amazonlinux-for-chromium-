# amazonlinux-for-chromium

An AmazonLinux container to build chromium

It's on [docker-hub](https://hub.docker.com/r/bokuweb/amazonlinux-for-chromium/) and [github](https://github.com/bokuweb/amazonlinux-for-chromium/)

## tags and links
* `latest` [(master/Dockerfile)](https://github.com/bokuweb/amazonlinux-for-chromium/blob/master/Dockerfile)


## how to build

```sh
git clone git@github.com:bokuweb/amazonlinux-for-chromium.git
cd amazonlinux-for-chromium
docker build --rm -t bokuweb/amazonlinux-for-chromium .
```

## running

```sh
docker run --rm  -it bokuweb/amazonlinux-for-chromium
```
