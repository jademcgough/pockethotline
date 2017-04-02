source 'http://rubygems.org'

ruby '2.4.1'
gem 'rails', '~> 3.2.22'
gem 'jquery-rails', '~> 1.0.18'
gem 'pg', '~> 0.11.0'
gem 'bcrypt-ruby', '~> 3.0.1', :require => 'bcrypt'
gem 'phone-validator', '~> 0.0.2'
gem 'twilio-ruby', "~> 3.5.0"
gem 'aws-s3', '~> 0.6.2', :require => 'aws/s3'
gem 'paperclip', '~> 2.4.5'
gem 'cocaine', '0.3.2' # required for paperclip version
gem 'delayed_job', '3.0.5'
gem 'delayed_job_active_record', '0.4.4'
gem 'rails_autolink', '~> 1.0.4'
gem 'will_paginate', '~> 3.0.4'
gem 'twitter', '~> 4.6.2'
gem 'stripe', '~> 1.5.24'
gem 'unicorn'
gem 'custom_configuration', '~> 0.0.2'

group :assets do
  gem 'haml'
  gem 'sass-rails', "  ~> 3.2.3"
  gem 'coffee-rails', "~> 3.2.1"
  gem 'uglifier', '~> 1.1.0'
end

group :development do
  # Just some stuff added for ease of development; feel free to
  # comment out anything temporarily if it gives you trouble.
  gem 'therubyracer'
  gem 'sqlite3'
  gem "rb-readline"
end

group :test do
  gem 'ffaker', '1.5.0'
  gem 'timecop'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 3.5.2'
  gem 'factory_girl_rails'
  gem 'capybara'
end
