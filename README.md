Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS(http://phantomjs.org).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/nathanbrakken/heroku-buildpack-phantomjs2.1.1.git

# or if your app is already created:
$ heroku buildpacks:add https://github.com/nathanbrakken/heroku-buildpack-phantomjs2.1.1

$ git push heroku master
```
