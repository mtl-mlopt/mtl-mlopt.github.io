source "https://rubygems.org"


# If you want to use GitHub Pages, remove the "gem "jekyll"" and uncomment "github-pages".
# gem "jekyll", "~> 4.3.1"
gem "github-pages", group: :jekyll_plugins
gem 'bulma-clean-theme'

gem "webrick"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
