ruby "2.2.3"
source 'https://rubygems.org'

gem 'shopify_app', '6.4.0'
# Bundle edge Rails instead:gem 'rails',github: 'rails/rails'
gem 'rails', '4.2.2'
# Use postgresql as the database for Active Record
gem'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~>5.0.2'
# Use Uglifier as compressor for JavaScript assests
gem 'uglifier', '>= 2.5.3'
# Use CoffeeScripts for ,coffee assets an views
gem 'coffee-rails', '4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem'therubyracer', platforms: :rubygems


gem 'bootstrap-sass', '3.3.6'
gem "compass"
gem "haml"
gem "heroku-nav"
gem "rake"
gem "rdiscount", "~> 1.6.x"
gem "sass"
gem "sinatra"
# Use jquery as the JavaScript library
gem 'jquery-rails', '4.0.3'
# Turbolinks makes following link in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '2.2.3'
# Build Json APIs with ease. Read more: https://github.com/rails/Jbuilder
gem 'jbuilder', '2.2.3'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~>3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'cucumber-rails', '1.2.1'
group :development, :test do
# Call 'bybug' anywhere in the code to stop execution and get a debugger console
gem 'byebug', '3.4.0'
 gem 'spring', '1.1.3'
  gem 'sqlite3', '1.3.9'
#Access an IRB console on expection page or by using <%= console%> in views
gem "web-console", '2.0.0.beta3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
group :test do
  gem "rack-test"
  gem "minitest-spec-context"
  gem "mocha"
end

group :packaging do
  gem "fog"
end
group :development do
  gem "shotgun"
end
