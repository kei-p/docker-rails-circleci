# docker-rails-circleci

```
$ docker=$(docker run -dit keip/docker-rails-circleci)
$ docker exec -it ${docker} /bin/sh -c "cat /tmp/.versions"
DOCKERFILE_VERSION 20180203
ruby 2.3.3p222 (2016-11-21 revision 56859) [x86_64-linux]
yarn 0.27.5
ChromeDriver 2.32.498513 (2c63aa53b2c658de596ed550eb5267ec5967b351)
Google Chrome 64.0.3282.140
```

### Build
```
$ docker build ./ --no-cache=true -t keip/docker-rails-circleci
```
