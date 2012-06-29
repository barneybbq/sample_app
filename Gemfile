source 'https://rubygems.org'

gem 'rails', '3.2.3'
gem 'bootstrap-sass'
gem 'bcrypt-ruby', '3.0.1'
gem 'therubyracer', :platforms => :ruby
gem 'faker', '1.0.1'
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.6'


group :development, :test do
  gem 'sqlite3'#, '1.3.5'
  gem 'rspec-rails'#, '2.10.0'
  gem 'annotate', '~> 2.4.1.beta'
  gem 'guard-rspec'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'#,   '3.2.4'
  gem 'coffee-rails'#, '3.2.2'
  gem 'uglifier'#, '1.2.3'
end

gem 'jquery-rails'#, '2.0.0'

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '0.8.8' if RUBY_PLATFORM =~ /linux/
  gem 'libnotify', '0.5.9' if RUBY_PLATFORM =~ /linux/
  gem 'rb-fchange', '0.0.5' if RUBY_PLATFORM =~ /win32/
  gem 'rb-notifu', '0.0.4' if RUBY_PLATFORM =~ /win32/
  gem 'win32console', '1.3.0' if RUBY_PLATFORM =~ /win32/
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.2'
  gem 'factory_girl_rails', '1.4.0'
  gem 'cucumber-rails', '1.2.1', require: false
  gem 'database_cleaner', '0.7.0'
  # Use if RUBY_PLATFORM =~ /darwin/ for Mac OSX
  # Use if RUBY_PLATFORM =~ /freebsd/ for FreeBSD
end 

group :production do
  gem 'pg', '0.12.2'
end