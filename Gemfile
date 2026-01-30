source "https://rubygems.org"

# Core Jekyll and Theme
gem "jekyll", "~> 4.4.1"
gem "jekyll-theme-primer"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag"
end

# Windows compatibility and environment-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Compatibility for JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
