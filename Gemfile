source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'
gem 'carrierwave', '~> 1.3', '>= 1.3.1'
gem 'faker', '~> 1.9', '>= 1.9.1'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'mini_racer', platforms: :ruby
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'bootstrap-will_paginate', '~> 1.0'
gem 'bootstrap-sass', '~> 3.4'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'

# Use ActiveStorage variant
 gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.4'
  gem 'minitest', '~> 5.11', '>= 5.11.3'
  gem 'minitest-reporters', '~> 1.3', '>= 1.3.6'
  gem 'guard', '~> 2.15'
  gem 'guard-minitest', '~> 2.4', '>= 2.4.6'
end

group :production do
  gem 'pg', '~> 1.1', '>= 1.1.4'
  gem 'fog', '~> 2.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
