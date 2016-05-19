# A Heroku Buildpack for Octopress

This is a fork of the official [Heroku Ruby Buildpack](https://github.com/heroku/heroku-buildpack-ruby) to add auto generation of an Octopress static site during deploy.

This means you don't have to run `rake generate` locally and commit the generated pages anymore. Heroku will run it for you.

Compatible with Heroku's Cedar-14 Stack.

# Usage:

Set your octopress blog to use this buildpack:

```
heroku buildpacks:set https://github.com/launchschool/heroku-buildpack-octopress
```

You can read about heroku buildpacks [here](https://devcenter.heroku.com/articles/buildpacks)

# Credit

Took some code from [Nicholas Mott's Version](https://github.com/nicholasmott/heroku-buildpack-octopress)
