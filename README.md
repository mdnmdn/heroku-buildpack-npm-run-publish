# Heroku Buildpack npm build

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for node applications that have a build step.

This will run `npm run build` at when heroku builds.

## Usage

1. Add the buildpack to heroku using

   ```bash
   $ heroku buildpacks:add https://github.com/romeovs/heroku-buildpack-npm-build
   ```
2. push your code.

