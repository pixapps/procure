source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.2'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'haml'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec-rails'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'  
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'rails-controller-testing'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
