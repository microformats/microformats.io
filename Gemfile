source "https://rubygems.org"
ruby "2.5.1"

# app server
gem "rails", "~> 5.1.0"

# database
gem "pg"

# webserver
gem "puma"

# webserver
gem "microformats", "~> 4.0.3"

# assets
gem "bootstrap", "~> 4.0.0.alpha6"
gem "sass-rails"
gem "autoprefixer-rails"
gem "uglifier"
gem "jquery-rails"

# bootstrap tooltips and popovers depend on tether for positioning
source "https://rails-assets.org" do
  gem "rails-assets-tether", ">= 1.1.0"
end

# dev and testing
group :development, :test do
  gem "byebug", platform: :mri
  gem "nokogiri"
  gem "rspec-rails"
  gem "rails-controller-testing"
  gem "guard-rspec"
  gem "spring-commands-rspec"
  gem "simplecov", :require => false
  gem "factory_girl_rails"
end

# dev
group :development do
  gem "web-console"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"

  # For measuring page/code performance
  gem "rack-mini-profiler"

  # For memory profiling
  gem "memory_profiler"

  # For call-stack profiling flamegraphs
  gem "flamegraph"
  gem "stackprof"
  gem "fast_stack"
end

# windows dev
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
