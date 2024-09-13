# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.0", ">= 7.0.1"

group :test do
  gem "html-proofer", "~> 5.0"
end

group :jekyll_plugins do
  #gem 'jekyll-admin'
  gem 'jekyll-avatar', '~> 0.8.0'
  gem 'jekyll-compose'
  #gem 'rackup'
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

#gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "webrick", "~> 1.7"