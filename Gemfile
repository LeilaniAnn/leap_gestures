source 'https://rubygems.org'
ruby '2.2.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# Use postgres as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
# Use Uglifier as compressor for JavaScript assets
# Use CoffeeScript for .coffee assets and views
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'puma'
group :assets do
  gem 'therubyracer'
  gem 'sass-rails', "  ~> 5.0"
  gem 'coffee-rails', "~> 4.1.0"
  gem 'uglifier'
gem 'turbo-sprockets-rails3'
  
end
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'rails', '4.2.5'
gem 'devise'
gem 'high_voltage'
gem 'unicorn'
gem 'unicorn-rails'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'better_errors'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rails_layout'
end
group :development, :test do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'

  source 'https://rails-assets.org' do
  gem 'rails-assets-angular-ui-grid'
  gem 'rails-assets-restangular'
  # Additional rails-assets gems go here...
end
end
gem 'sprockets-rails'

gem 'bootstrap', '~> 4.0.0.alpha3'

source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end