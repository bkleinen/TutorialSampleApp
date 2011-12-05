source 'http://rubygems.org'

gem 'rails', '3.1.3'

gem 'gravatar_image_tag', '1.0.0.pre2'
gem 'will_paginate', '~> 3.0'
gem 'multi_json'
gem 'jquery-rails'

group :development, :test do
  gem 'sqlite3' 
end

group :production do
  gem 'pg'
end

group :development do
  gem 'rspec-rails', '2.6.1'
  gem 'annotate', '2.4.0'
  gem 'faker', '0.3.1'
end


group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'spork', '0.9.0.rc5'
  gem 'factory_girl_rails', '1.0'
end

# Gems used only for assets and not required
# in production environments by default.
# Asset template engines
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :test do
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
end
