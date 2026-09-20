source "https://rubygems.org"

# Jekyll (using 4.2.x for Ruby 2.6 compatibility)
gem "jekyll", "~> 4.2.0"

# Jekyll plugins
gem "jekyll-sitemap"
gem "jekyll-gist"
gem "jekyll-feed"

# Platform dependencies
gem "webrick", "~> 1.7"

# Windows 时区支持
# Jekyll 的 lib/jekyll/utils/win_tz.rb 在 Windows 上会强制 require "tzinfo"，
# 缺了它会直接抛 MissingDependencyException 导致 jekyll serve 失败。
# tzinfo-data 提供时区数据库（Windows 没有系统 zoneinfo）。
# 注意：这里不加 platforms 限制 —— RubyInstaller 的 UCRT 构建平台标识为
# x64-mingw-ucrt，用 platforms: [:x64_mingw] 有可能匹配不上而被跳过。
gem "tzinfo", "~> 2.0"
gem "tzinfo-data"
