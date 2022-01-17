# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in bootsnap.gemspec
gemspec

if ENV["PSYCH_4"]
  gem "psych", ">= 4"
end

gem "bundler"
gem "rake"
gem "rake-compiler"
gem "minitest", "~> 5.0"
gem "mocha", "~> 1.2"

group :development do
  gem "rubocop", "0.81.0" # Ruby 2.3 support
  gem "rubocop-shopify", require: false
  gem "byebug", platform: :ruby
end
