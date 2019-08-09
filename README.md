# Heroku Buildpack npm publish (or custom command)

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for node applications that have a build step.

This will run `npm run publish` at when heroku builds.

## Usage

1. Add the buildpack to heroku using

   ```bash
   $ heroku buildpacks:add https://github.com/romeovs/heroku-buildpack-npm-build.git
   ```
2. push your code.

## Custom command

Use the optional environment variable *NPM_CUSTOM_RUN_COMMAND* to run a different `npm run *command*`.