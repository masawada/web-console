source 'https://rubygems.org'

gemspec

gem 'rails', github: 'rails/rails'

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'binding_of_caller', '0.7.3.pre1'
end

platforms :ruby do
  gem 'sqlite3'
end

group :test do
  gem 'rake'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end
