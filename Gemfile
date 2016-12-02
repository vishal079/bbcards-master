source "https://rubygems.org"

group :development, :test do
  gem "heroku_hatchet"
  gem "rspec-core"
  gem "rspec-expectations"
  gem "excon"
  gem "rake"
  gem "parallel_tests"
  gem 'rspec-retry'
  gem "netrc"
  gem "git", github: "hone/ruby-git", branch: "master"
  gem 'json', '~> 2.0.2'
  gem 'ruby', '2.2.6'
  gem 'rails', '4.0.0'
  group :production do
    gem 'pg'
  end
  group :development do
    gem 'sqlite3'
  end
end
