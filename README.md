# Procfile
A [Procfile](https://devcenter.heroku.com/articles/procfile) is a mechanism for declaring what commands are run by your application’s dynos on the Heroku platform.

## How applications are launched during dyno boot

for launching PHP & Apache, you would run:

    vendor/bin/heroku-php-apache2

for launching HHVM & Nginx the command would be:

    vendor/bin/heroku-hhvm-nginx --help

## Copyright and License

Code released under the [MIT](https://opensource.org/licenses/MIT) license.