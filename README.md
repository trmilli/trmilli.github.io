# trmilli.github.io

This repository hosts the source  for <https://trmilli.github.io>.
 

## Building and testing the site

The site is built using [jekyll](https://jekyllrb.com).  Content in the `docs` directory is served by github pages.

Use the `draft` directory to test new content.  Within the `draft` directory, run a local server with 

    bundle exec jekyll serve --watch

When you've tested new or modified content, copy it to the `docs` directory.  Do *not* copy `Gemfile` or `_config.yml`: these are configured for use with a locally running server.