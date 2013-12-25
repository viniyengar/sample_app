source 'https://rubygems.org'
#VI = Current line commented by VI and next line added by VI
#VI
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

#VI
group :development do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

# Use sqlite3 as the database for Active Record
#VI gem 'sqlite3'

# Use SCSS for stylesheets
#VI gem 'sass-rails', '~> 4.0.0'
gem 'sass-rails', '4.0.1'

# Use Uglifier as compressor for JavaScript assets
#VI gem 'uglifier', '>= 1.3.0'
gem 'uglifier', '2.1.1'

# Use CoffeeScript for .js.coffee assets and views
#VI gem 'coffee-rails', '~> 4.0.0'
gem 'coffee-rails', '4.0.1'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
#VI gem 'jquery-rails'
gem 'jquery-rails', '3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#VI gem 'turbolinks'
gem 'turbolinks', '1.1.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
#VI gem 'jbuilder', '~> 1.2'
gem 'jbuilder', '1.0.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  #VI gem 'sdoc', require: false
  gem 'sdoc', '0.3.20', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end