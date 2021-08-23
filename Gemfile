source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in importmap-rails.gemspec.
gemspec

rails_version = ENV["RAILS_VERSION"] || "6.1.0"
gem "rails", ">= 6.1.4.1", "~> #{rails_version}"

gem "sqlite3"

group :test do
  gem "turbo-rails", ">= 0.6.0"
  gem "stimulus-rails", ">= 0.2.4"

  gem "byebug"

  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
