source 'https://rubygems.org'
ruby '2.5.1'

# app server
gem 'rails', '~> 5.2.0'

# database
gem 'pg'

# webserver
gem 'puma'

# webserver
gem 'microformats'

# assets
gem 'autoprefixer-rails'
gem 'bootstrap'
gem 'jquery-rails'
gem 'sass-rails'
gem 'uglifier'

# dev and testing
group :development, :test do
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails'
  gem 'guard-rspec'
  gem 'nokogiri'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'simplecov', require: false
  gem 'spring-commands-rspec'
end

# dev
group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console'

  # For measuring page/code performance
  gem 'rack-mini-profiler'

  # For memory profiling
  gem 'memory_profiler'

  # For call-stack profiling flamegraphs
  gem 'fast_stack'
  gem 'flamegraph'
  gem 'stackprof'

  gem 'rubocop'
end

# windows dev
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
