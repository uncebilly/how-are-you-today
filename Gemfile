# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "bootstrap", "~> 4.1.1"
gem "coffee-rails", "~> 4.2"
gem "devise"
gem "faraday", "~> 0.15.2"
gem "haml"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "materialize-sass"
gem "pg", ">= 0.18", "< 2.0"
gem "prawn-rails"
gem "puma", "~> 3.7"
gem "rails", "~> 5.2.0"
gem "redis"
gem "rubocop", require: false
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "capybara", "~> 2.13"
  gem "factory_bot_rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.7"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :test do
  gem "database_cleaner"
end

ruby "2.5.1"
