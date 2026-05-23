source "https://rubygems.org"

# Use the github-pages meta-gem to match GitHub's build environment exactly.
gem "github-pages", group: :jekyll_plugins

# Plugins enabled in _config.yml
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows-specific gems needed if Jekyll ever runs locally on Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1"
end
