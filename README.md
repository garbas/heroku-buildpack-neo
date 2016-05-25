# Heroku buildpack: neo

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for running a ``node_modules/.bin/neo build`` in your project. It doesn’t do
anything else, so to actually install node packages you also need to setup
[heroku/nodejs](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-nodejs)
buildpack before neo buildpack.
