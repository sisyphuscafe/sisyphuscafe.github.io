source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

if ENV['JEKYLL_LOCAL']
  # Local development only:
  #gem "jekyll", "~> 4.3.3"
  gem "jekyll"
  # Let's try out the minimal mistakes theme as a gemfile.
  gem "minimal-mistakes-jekyll"
else
  # When publishing to GitHub Pages. To upgrade, run `bundle update github-pages`.
  gem "github-pages", group: :jekyll_plugins
end

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-include-cache"
end

gem "tzinfo-data"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
#platforms :mingw, :x64_mingw, :mswin, :jruby do
#  gem "tzinfo", ">= 1", "< 3"
#  gem "tzinfo-data"
#end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
#gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
