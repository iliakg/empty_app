source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '2.7.1'

# rails
gem 'rails', '~> 6.1.4'

# database
gem 'pg'

# server
gem 'puma', '~> 5.0'

# fronteend
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'

gem 'pry'
gem 'bootsnap', require: false

group :development, :test do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'ffaker'
  gem 'rubocop', require: false
end

group :test do
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'database_cleaner'
end
