source "https://rubygems.org"

# Require jekyll 3.8.5 for github pages
gem "jekyll", "3.8.5" 

# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "github-pages",     "203"
  gem "jekyll-feed",      "0.13.0"
  gem "jekyll-paginate",  "1.1.0"
  gem "jekyll-sitemap",   "1.4.0"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

