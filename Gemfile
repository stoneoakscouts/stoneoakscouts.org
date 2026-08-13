# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 4.4.1"
gem "jekyll-sass-converter", "~> 3.1"

# Jekyll 4.4 still allows Liquid 4.0.3, which calls String#tainted?
# (removed in Ruby 3.2).
gem "liquid", "~> 4.0.4"
