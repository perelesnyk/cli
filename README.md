Drush and Composer
==================


|Drush Version | Tags|Dockerfile|
|--------|---------------|------------|
|8.1.15| `7.1-alpine-cli-1.0.9` |  |
|9.0+| `7.1-alpine-cli-1.0.12` | [Dockerfile-alpine-cli-7.1](https://github.com/digitalpulp/cli/blob/master/8/Dockerfile-alpine-cli-7.1)|
|8.1.15|`5.6-alpine-1.0.4` | [Dockerfile-alpine-cli-5.6](https://github.com/digitalpulp/cli/blob/master/8/Dockerfile-alpine-cli-5.6)|
| .|codeship|[Dockerfile-codeship](https://github.com/digitalpulp/cli/blob/master/8/Dockerfile-codeship)|

Both Drush and Drupal Console expect to be installed in the Drupal vendor directory.  This
container expects the project to be mounted at `/var/www` and sets `/var/www/vendor/bin` as
a PATH component.
