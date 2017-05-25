## To get started

```sh
$ echo '.gems' > .rbenv-gemsets
$ bundle install
$ yarn install
```

## Why Bourbon? Why not the newest Neat grid?

Neat 2.0 baffles me, and 1.8 it depends on Bourbon 4.x. I'll move onto a new grid but this supports several existing projects of mine.

## What's Cloudcannon got to do with it?

You can strip them out, but there are conditionals in the markup and settings in `_config.build.yml` that let the site work in the Cloudcannon CMS. The assumptiom is that the site will be deployed to production elsewhere (e.g. Netlify, etc.)
