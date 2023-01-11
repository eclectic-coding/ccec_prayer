source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis"
gem "bootsnap", require: false
gem "bcrypt"

# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "standard", "~> 1.9", require: false
  gem "capybara"
  gem "webdrivers"
  gem "rspec-rails", "~> 6.0.0"
  gem "factory_bot_rails"
  gem "faker"
end

group :development do
  gem "web-console"
  gem "fuubar", "~> 2.5", ">= 2.5.1"
  gem "guard"
  gem "guard-rspec"
  gem "rubocop"
  gem "rubocop-rails", require: false
  gem "rubocop-rspec"
end

group :test do
  gem "simplecov", "~> 0.21.2", require: false
end
