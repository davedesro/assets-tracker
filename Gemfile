source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.1'
gem 'pg'

gem 'json'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'bootstrap-sass', '~> 3.0.2.1'
  gem 'sass-rails',   '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.3.0'
end

group :development, :test do
  gem "guard", "~> 2.2.4"
  gem 'rb-fsevent', '~> 0.9.2'
  gem 'capybara'
end

group :development do
  gem 'guard-livereload'
  gem 'rack-livereload'
end

group :test do
  gem "spork", '1.0.0rc4'
  gem 'guard-spork'
  gem 'vcr'
  gem 'fakeweb'
  gem 'timecop'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
end

gem 'jquery-rails'
gem 'rspec-rails'
gem 'haml'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]