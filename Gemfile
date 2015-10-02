source 'https://rubygems.org'



gem 'rails', '4.2.1'
gem 'mysql2'

gem 'thin' # server
gem 'backbone-on-rails' # backbone.js
gem 'devise' # user authentication
gem 'bcrypt', '~> 3.1.7' # salt & hash
gem 'jquery-rails' # jquery
gem 'turbolinks' # fast pages
gem 'jbuilder', '~> 2.0' # json
# gem 'therubyracer', platforms: :ruby # js runtime

gem 'sdoc', '~> 0.4.0', group: :doc

group :assets do
  gem 'sass-rails', '~> 5.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.1.0'
end

group :development, :test do
  gem 'byebug' # debugging
  gem 'web-console', '~> 2.0' # IRB console <%= console %>
  gem 'spring' # run on background
  gem 'spring-commands-rspec'

  gem 'rspec-rails' # respec for rails
  gem 'spork-rails' # for quickly running spec on a dedicated port
end

group :development do
  gem 'better_errors' # detailed error pages
  gem 'bullet' # check N+1 queries, counter caching, and eager loading
  gem 'capistrano-rails' # deployment
  gem 'capistrano-rvm' # RVM on capistrano
end

group :test do
  gem 'capybara' # integration specs that require interacting with rails views
  gem 'database_cleaner' # for clearing the database before and after specs
  gem 'factory_girl_rails' # for creating models in specs
  gem 'shoulda-matchers', require: false # shoulda
end
