# docker-rails-circleci

```
$ docker=$(docker run -dit keip/docker-rails-circleci)
$ docker exec -it ${docker} /bin/sh -c "ruby -v && echo \"yarn \$(yarn --version)\" && chromedriver -v && google-chrome --version"
ruby 2.3.3p222 (2016-11-21 revision 56859) [x86_64-linux]
yarn 0.27.5
ChromeDriver 2.32.498513 (2c63aa53b2c658de596ed550eb5267ec5967b351)
Google Chrome 63.0.3239.132
```
