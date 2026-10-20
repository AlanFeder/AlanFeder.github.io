# AlanFeder.github.io

Use Ruby 3.3 to build and preview the site:

```sh
bundle install
bundle exec jekyll serve
```

To run the production build and check the locked dependencies for known
vulnerabilities:

```sh
JEKYLL_ENV=production bundle exec jekyll build
bundle exec bundler-audit check --update
```

The Gemfile lists Jekyll 3.10 and the site's plugins directly. The `github-pages`
bundle includes unused themes and pins `jekyll-remote-theme` to a version that
requires vulnerable rubyzip releases. This site keeps its layouts and Sass
locally, so it does not need that dependency.

GitHub Pages still deploys from `main` using GitHub's hosted builder and its own
dependency versions. The Ruby workflow checks this repository's bundle; it does
not deploy the site or change the Pages settings.

Dependabot checks Ruby dependencies weekly and groups version updates so related
gems can update together. Commit both `Gemfile` and `Gemfile.lock` when changing
dependencies.
