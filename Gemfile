source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
ruby '1.9.3'

gem 'rails', '4.0.0.rc2'
gem 'devise', '3.0.0.rc'
gem 'simple_form'
gem "paperclip", "~> 3.0"
gem 'protected_attributes'
gem 'aws-sdk'

# Use sqlite3 as the database for Active Record
group :production do
  gem 'pg'
  gem 'thin'
end

group :development, :test do
  gem 'sqlite3'
end

# Use SCSS for stylesheets
#group :assets do
  gem 'sass-rails', '~> 4.0.0.rc2'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'bootstrap-sass', '~>2.2.2.0'
#end
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
