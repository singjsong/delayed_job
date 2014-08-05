source 'https://rubygems.org'

gem 'rake'

platforms :ruby do
  gem 'sqlite3'
end

platforms :jruby do
  gem 'jruby-openssl'
  gem 'activerecord-jdbcsqlite3-adapter'
end

group :test do
  gem 'activerecord', (ENV['RAILS_VERSION'] || ['>= 3.2', '< 4.2'])
  gem 'actionmailer', (ENV['RAILS_VERSION'] || ['>= 3.2', '< 4.2'])
  gem 'coveralls'
  gem 'rspec', '>= 3'
  gem 'rubocop', '>= 0.23'
  gem 'simplecov', '>= 0.9'
end

gemspec
