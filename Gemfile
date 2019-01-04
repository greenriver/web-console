# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gemspec

gem "rails", github: "rails/rails", branch: 'master', ref: '548bd50'
gem "arel", github: "rails/arel", branch: 'master', ref: 'aae413b'
gem "rack", github: "rack/rack", branch: 'master', ref: '461099b'

group :development do
  platform :ruby do
    gem "byebug"
  end
  gem "puma"
end

group :test do
  gem "rake"
  gem "mocha", require: false
  gem "simplecov", require: false
end
