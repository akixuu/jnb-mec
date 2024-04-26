# After updating, run 'bundle install' or 'bundle exec jekyll serve'

source "https://rubygems.org"


gem "github-pages", group: :jekyll_plugins # to upgrade, run `bundle update github-pages

group :jekyll_plugins do
  gem 'jekyll-sass-converter'
  gem 'jekyll-loading-lazy'
  gem 'jekyll-feed', "~> 0.12"
end

gem 'webrick'

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
gem "tzinfo", ">= 1", "< 3"
gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]


# lsi: false
# safe: true
# source: mecoop
# incremental: false
# highlighter: rouge
# gist:
#   noscript: false
# kramdown:
#   math_engine: mathjax
#   syntax_highlighter: rouge