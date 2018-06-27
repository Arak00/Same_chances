# frozen_string_literal: true

source 'https://rubygems.org'

# authentification
gem 'devise'
# gem 'pundit'

gem 'bootsnap'
gem 'bootstrap-sass'
gem 'coffee-rails'
gem 'dotenv'
gem 'google-api-client', require: 'google/apis/analytics_v3'
gem 'jbuilder'
gem 'jquery-rails'
gem 'mailjet'
gem 'nokogiri'
gem 'omniauth-google-oauth2'
gem 'pg', '0.20.0'
gem 'puma'
gem 'rails'
gem 'sass-rails'
gem 'sendgrid-ruby'
gem 'trestle'
gem 'trestle-auth'
gem 'trestle-search'
gem 'turbolinks'
gem 'twitter'
gem 'uglifier'

group :development, :test do
  gem 'byebug', '9.0.6', platform: :mri
  gem 'database_cleaner'
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'simplecov'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
  gem 'listen'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'nyan-cat-formatter'
  gem 'poltergeist'
  gem 'rspec_junit_formatter'
  gem 'safe_attributes'
  gem 'shoulda-matchers'
end

group :production do
  gem 'sentry-raven'
  gem 'skylight'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
ruby File.read('./.ruby-version')
