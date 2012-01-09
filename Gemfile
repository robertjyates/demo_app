source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Commented out gem 'sqlite3'
# From http://stackoverflow.com/questions/7296683/rails-3-1-pushing-to-heroku-errors-installing-postgres-adapter
# http://devcenter.heroku.com/articles/how-do-i-use-sqlite3-for-development
group :production do
  gem 'therubyracer'
  gem 'pg'
end
group :development, :test do
  gem 'sqlite3'
end

gem 'json'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'

