source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.2.2'
gem 'pg', '~> 1.0'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '~> 4.1', '>= 4.1.18'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5.1', '>= 5.1.1'
gem 'jbuilder', '~> 2.7'
gem 'aws-sdk-s3', '~> 1.25'

# Backgroud worker
gem 'hiredis', '~> 0.6.1'
gem 'sidekiq', '~> 6.4'

# Spree-commerce
gem 'spree', '~> 3.7'
gem 'spree_auth_devise', '~> 3.5'
gem 'spree_gateway', '~> 3.3'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'factory_bot'
  gem 'pry-rails'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
