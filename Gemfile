source 'https://rubygems.org'

ruby "2.3.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.9'
# Use sqlite3 as the database for Active Record
group :development do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  gem 'pry-rails'
  gem 'dotenv-rails'
end

group :production do
  gem 'pg'
  #  enable all platform features for heroku
  gem 'rails_12factor'
end
# Use SCSS for stylesheets
# gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
gem 'better_errors', group: [:development, :test]
gem "binding_of_caller", group: [:development, :test]

# Foundation for style
gem 'foundation-rails', '~> 5.5.0'
gem 'sass-rails', '~>5.0.0'
gem 'devise'

# Using Redis to build a shopping cart from scratch
gem 'redis', '~> 3.0.1'
gem 'hiredis', '~> 0.4.5'

# for fast webserver & pushing to heroku
gem 'thin', '~> 1.6.3'

# braintree for payment
gem 'braintree', '~> 2.33.1'

# figaro does the samething you would do with your .env file (keeps config out of git)
gem 'figaro', '~> 0.7.0'

# Gon allows us to set variables in our controllers and then access them from JavaScript
gem 'gon', '~> 5.1.2'