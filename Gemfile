source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.1"

gem "rails", "~> 6.0.3", ">= 6.0.3.2"
gem "mysql2", "~> 0.5.3"
gem "puma", "~> 4.1"
gem "sass-rails", ">= 6"
gem "webpacker", "~> 4.0"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.7"
gem "bootsnap", ">= 1.4.2", require: false
gem "config"
gem "bootstrap-sass" 
gem "bcrypt", "3.1.13"
gem "faker" , "2.1.2"
gem "kaminari", "~> 0.16.3"
gem "kaminari-bootstrap", "~> 3.0", ">= 3.0.1"
gem "figaro", "~> 1.1", ">= 1.1.1"
gem "active_storage_validations", "~> 0.1"
gem "image_processing", "~> 0.2.3"
gem "mini_magick", "~> 4.5", ">= 4.5.1"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :development, :test do
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
