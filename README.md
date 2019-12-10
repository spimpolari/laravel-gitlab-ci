# Laravel Gitlab CI rules

This is a modification of the [lorisleiva/laravel-docker](https://github.com/lorisleiva/laravel-docker) container.

### Supported tags and respective `Dockerfile` links
* [7.4](https://github.com/andrey-helldar/laravel-gitlab-ci/blob/master/7.4/Dockerfile), [latest](https://github.com/andrey-helldar/laravel-gitlab-ci/blob/master/latest/Dockerfile)
* [7.3](https://github.com/andrey-helldar/laravel-gitlab-ci/blob/master/7.3/Dockerfile)


### Modified:
* The installed versions of `nodejs` and `yarn` are replaced with the latest ones. By default, versions nodejs 10.x and yarn 1.16.x were installed.
* Added installation of php-soap extension.
* Added installation of php-redis extension.
