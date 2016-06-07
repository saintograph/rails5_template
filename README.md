# README

Snapshot of gems:

gem 'rails', '>= 5.0.0.rc1', '< 5.1'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5.x'
gem 'jbuilder', '~> 2.0'

gem 'bootstrap-sass'
gem 'autoprefixer-rails'
gem 'haml-rails'
gem 'carrierwave'
gem 'mini_magick'
gem 'devise'
gem 'country_select'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'html2haml'
end

group :test do
  gem 'faker'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver' 
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'pg'
