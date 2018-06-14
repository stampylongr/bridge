# frozen_string_literal: true

source 'https://rubygems.org'
ruby '>= 2.3.0', '< 2.6.0'

gem 'rails', '~> 5.2.0'
gem 'pg', '~> 0.20'
gem 'puma', '~> 3.10'
gem 'sass-rails', '~> 5.0'
gem 'font-awesome-rails'
gem 'jquery-rails'
gem 'uglifier'

gem 'bootsnap'
gem 'mastodon-api', require: 'mastodon', git: 'https://github.com/tootsuite/mastodon-api'
gem 'twitter', git: 'https://github.com/sferik/twitter'
gem 'devise', '~> 4.4'
gem 'omniauth-twitter'
gem 'omniauth-mastodon', '>= 0.9.2'
gem 'hamlit-rails'
gem 'fast_blank', '~> 1.0'
gem 'dotenv-rails', '~> 2.2'
gem 'http'
gem 'httplog', '~> 0.99'
gem 'hiredis', '~> 0.6'
gem 'redis', '~> 3.3', require: ['redis', 'redis/connection/hiredis']
gem 'sidekiq', '~> 5.0'
gem 'sidekiq-status'
gem 'redis-rails'
gem 'oj'
gem 'react_on_rails', '11.0.0'

group :development, :test do
  gem 'pry-rails', '~> 0.3'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'better_errors', '~> 2.4'
  gem 'binding_of_caller', '~> 0.7'
end

group :production do
  gem 'lograge'
  gem 'rails_12factor'
end

gem 'mini_racer', platforms: :ruby
gem 'webpacker', '~> 3.5'
