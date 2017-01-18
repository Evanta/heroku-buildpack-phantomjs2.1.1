Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS(http://phantomjs.org).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/Evanta/heroku-buildpack-phantomjs2.1.1

# or if your app is already created:
$ heroku buildpacks:add https://github.com/Evanta/heroku-buildpack-phantomjs2.1.1

$ git push heroku master
```
```
Shrimp needs Phantomjs
     _.--------,..
   ;:____________ `--,_
  (_.-(o)-,-,-.. `''--,_
    ''-.__)_)_,'`\
        /||//| )-;
        ||\ |/
        '' ' (/) ldb
```
