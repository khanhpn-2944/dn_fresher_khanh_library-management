source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.7.1"

gem "active_storage_validations", "~> 0.9.7"
gem "bcrypt", "~> 3.1.7"
gem "bootsnap", ">= 1.4.4", require: false
gem "bootstrap-sass", "3.4.1"
gem "cloudinary", "~> 1.22"
gem "config"
gem "devise"
gem "faker", "2.1.2"
gem "image_processing", "~> 1.12", ">= 1.12.2"
gem "jbuilder", "~> 2.7"
gem "mysql2", "~> 0.5"
gem "pagy", "~> 5.10", ">= 5.10.1"
gem "puma", "~> 5.0"
gem "rails", "~> 6.1.4", ">= 6.1.4.1"
gem "rails-i18n"
gem "rake", "13.0.6"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)
gem "webpacker", "~> 5.0"

group :development, :test do
  gem "debug", platforms: %i(mri mingw x64_mingw)
  gem "factory_bot_rails"
  gem "pry"
  gem "rspec-rails"
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

group :development do
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "spring"
  gem "web-console", ">= 4.1.0"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "database_cleaner", "~> 1.5"
  gem "rails-controller-testing"
  gem "selenium-webdriver"
  gem "shoulda-matchers", "~> 5.0"
  gem "simplecov"
  gem "simplecov-rcov"
  gem "webdrivers"
end
