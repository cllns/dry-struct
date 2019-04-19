source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gemspec

gem 'dry-logic', github: 'dry-rb/dry-logic', branch: 'master'
gem 'dry-types', github: 'dry-rb/dry-types', branch: 'master'

group :test do
  gem 'codeclimate-test-reporter', platform: :mri, require: false
  gem 'simplecov', require: false
  gem 'warning'
end

group :tools do
  gem 'pry'
  gem 'pry-byebug', platform: :mri
end

group :benchmarks do
  gem 'sqlite3'
  gem 'activerecord'
  gem 'benchmark-ips'
  gem 'virtus'
  gem 'fast_attributes'
  gem 'attrio'
  gem 'hotch'
end
