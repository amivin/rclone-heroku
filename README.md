# rclone-heroku

A Heroku buildpack for rclone that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/amivin/rclone-heroku.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/amivin/rclone-heroku.git
