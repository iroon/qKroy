source 'https://rubygems.org'

gem 'rails', '~> 4.2.6'
gem 'pg'
gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'turbolinks'
gem 'i18n-tasks'
gem 'jbuilder'

gem 'spree', github: 'spree/spree'
gem 'spree_auth_devise', github: 'spree/spree_auth_devise'
gem 'spree_gateway', github: 'spree/spree_gateway'

gem 'deface', github: 'spree/deface'
gem 'settingslogic'
gem 'globalize'
gem 'globalize-accessors'
gem 'json'
gem 'rest-client'
gem 'stomp'
gem 'pointpin'
gem 'font-awesome-rails'
gem 'foundation-rails'
gem 'high_voltage', '~> 3.0.0'
gem 'rollbar'
gem 'whenever', require: false
gem 'cocoon'

# moved to general because we deploy via Semaphore
# gem 'capistrano', '~> 3.4'
# gem 'capistrano-passenger', '~> 0.2.0', require: false
# gem 'capistrano-rvm', '~> 0.1.2', require: false
# gem 'capistrano-rails', '~> 1.1', '>= 1.1.6', require: false

group :development do
  gem 'web-console', '~> 2.0'
end

group :development, :test do
  gem 'dotenv-rails'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'shoulda-matchers'
  gem 'byebug'
  gem 'spring'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'
  gem 'database_cleaner'
end

group :test do
  gem 'capybara-webkit'
  gem 'vcr'
  gem 'webmock'
  gem 'simplecov', require: false
end