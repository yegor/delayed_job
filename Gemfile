source 'https://rubygems.org'

gem  'rake'

platforms :ruby do
  gem 'sqlite3'
end

platforms :jruby do
  gem 'jruby-openssl'
  gem 'activerecord-jdbcsqlite3-adapter'
end

group :test do
  gem 'activerecord'
  gem 'actionmailer'
  gem 'rspec', '>= 2.11'
  gem 'simplecov', :require => false
  gem 'coveralls', :require => false
end

gemspec
