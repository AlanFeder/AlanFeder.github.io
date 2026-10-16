source 'https://rubygems.org'

ruby '~> 3.3.0'

# Keep the GitHub Pages Jekyll/Sass generation, but install only the plugins
# this site uses. github-pages also pins unused remote themes to rubyzip < 3.
gem 'jekyll', '~> 3.10.0'
gem 'kramdown-parser-gfm', '~> 1.1'

group :jekyll_plugins do
    gem 'jekyll-seo-tag'
    gem 'jekyll-gist'
    gem 'jekyll-feed'
    gem 'jemoji'
    gem "jekyll-paginate-v2", "~> 2.0"
end

group :test do
    gem 'html-proofer', '~> 4.4'
    gem 'bundler-audit', '~> 0.9'
end

gem "webrick", "~> 1.8"
