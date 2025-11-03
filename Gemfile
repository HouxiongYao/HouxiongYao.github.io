source "https://rubygems.org"

# 使用 GitHub Pages 官方环境（包含 Jekyll v3.10.0 与所有支持插件）
gem "github-pages", "~> 232", group: :jekyll_plugins

# 默认主题可以删掉或改成自己的
# gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
