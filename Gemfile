# frozen_string_literal: true

source "https://rubygems.org"

# Use the github-pages gem to match the GitHub Pages server environment
gem 'github-pages', group: :jekyll_plugins

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :jekyll_plugins do
    # List any additional plugins that you want to use and are supported by GitHub Pages
    # Note: Some plugins, like jekyll-feed and jekyll-sitemap, are already included with github-pages
    gem 'jekyll-feed'
    gem 'jekyll-sitemap'
    gem 'jekyll-paginate'
    gem 'jekyll-seo-tag'
    gem 'jekyll-archives'
end

# Windows Directory Monitor for better performance on Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

gem 'webrick', '~> 1.7'

gem 'csv'
