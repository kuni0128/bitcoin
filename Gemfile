source 'http://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.3'
gem 'sqlite3'
gem 'bcrypt', '~> 3.1'
gem 'puma', '~> 3.0'
gem 'bootstrap-sass', '~> 3.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'slim-rails', '~> 3.1'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec-rails', '~> 3.7'
  gem 'factory_bot_rails', '~> 4.8'
  gem 'guard-rspec', '~> 4.7'
  gem 'spring-commands-rspec', '~> 1.0'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'faker', '~> 1.8'
  gem 'capybara', '~> 2.15'
  gem 'database_cleaner', '~> 1.6'
  gem 'launchy', '~> 2.4'
  gem 'selenium-webdriver', '~> 3.7'
  gem 'shoulda-matchers', '~> 3.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

