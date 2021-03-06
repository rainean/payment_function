source 'http://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.2'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# For authentication
gem 'devise'
# For error logging
gem 'rollbar'
#  Use semantic-ui for the UI of the site
gem 'semantic-ui-sass'
# Generates slim templates instead of erb
gem 'slim-rails'
# for Globe Labs API
gem 'globe_connect', git:'https://github.com/globelabs/globe-connect-ruby.git'
# for rspec tests
gem 'webmock'
gem 'vcr'


group :production do
  # Makes running Rails app easier, based on 12factor.net
  gem 'rails_12factor'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'binding_of_caller'
  # For testing user interactions on app
  gem 'capybara'
  # For cleaning db between tests
  gem 'database_cleaner'
  # Loads environment variables from .env
  gem 'dotenv-rails'
  # Fixtures replacement for testing
  gem 'factory_girl_rails'
  # Fixtures replacement for testing
  gem 'faker'
  # Launches external applications e.g. browser from test suite
  gem 'launchy'
  # Enables rails console to open pry
  gem 'pry-rails'
  #  Rails testing framework
  gem 'rspec-rails', '~> 3.5'
  # Ruby code analyzer based on Ruby Style Guide
  gem 'rubocop', '~> 0.47.1', require: false
  # Rubocop for RSpec
  gem 'rubocop-rspec'
end

group :development do
  # Replaces default Rails error page for better debugging
  gem 'better_errors'
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
