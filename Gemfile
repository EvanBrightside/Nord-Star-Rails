source 'https://rubygems.org'
git_source :github do |repo|
  "https://github.com/#{repo}.git"
end

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

gem 'redis'
gem 'sidekiq'
gem 'sentry-raven'

gem 'actiontext', github: 'rails/actiontext', require: 'action_text', ref: 'cfe4674d3637c746cdb3c2b5131e2de498775529'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'dotenv-rails'

group :development, :test do
  gem 'pry'
  gem 'rubyzip', '>= 1.2.2'
  gem 'faker'
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'letter_opener'
  # capistrano
  gem 'capistrano', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-rvm', require: false
  gem 'capistrano3-unicorn', require: false
  gem 'capistrano-sidekiq', require: false

  gem 'pry-rails'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

group :production, :staging do
  gem 'unicorn'
  gem 'therubyracer', platforms: :ruby
end

group :lint do
  gem 'rubocop'
end

# ActiveAdmin
gem 'activeadmin'
gem 'cancan'
gem 'devise'
gem 'activeadmin-searchable_select'
gem 'active_admin_datetimepicker'
gem "active_admin_import" , github: "activeadmin-plugins/active_admin_import"

gem 'seed_dump'

gem 'arctic_admin'
gem "font-awesome-rails"

gem 'carrierwave'
gem 'carrierwave-video-thumbnailer'
gem 'mini_magick'

gem 'slim-rails'
gem 'jquery-rails'
gem 'sprockets'
gem 'autoprefixer-rails', '8.6.5'
gem 'select2-rails'
gem 'bootstrap-datepicker-rails'
gem 'jquery-simplecolorpicker-rails'
gem 'autosize-rails'

gem 'whenever', require: false
gem 'capistrano-db-tasks', require: false
gem 'cancancan'
gem 'role_model'
gem 'simple_form'
gem 'friendly_id'
gem 'babosa'
gem 'sanitize'
gem 'awesome_nested_set'
gem 'cocoon'
gem 'russian'
gem 'kaminari'
gem 'paper_trail'
gem 'scoped_search'
gem 'enumerize'
gem "globalize"
gem 'tzinfo-data', platforms: %w[mingw mswin x64_mingw jruby]
