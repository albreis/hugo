# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm"
gem 'jekyll-admin', group: :jekyll_plugins
gem 'jekyll-manager', group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-gist"
end
