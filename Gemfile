source 'https://rubygems.org'

ruby '2.6.6'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.11'
gem "factory_bot_rails"
gem 'simplecov', require: false, group: :test
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
gem "clearance"


# Use Unicorn as the app server
# gem 'unicorn'

gem 'themoviedb'

# Window support
gem 'tzinfo'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
group :development do
    gem 'web-console', '~> 2.0'
end
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  gem 'rspec-rails'
  gem 'guard-rspec'

  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '~> 1.3.6'

  # Access an IRB console on exception pages or by using <%= console %> in views

  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'
  gem 'pry-byebug'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'cucumber-rails-training-wheels'
  gem 'simplecov', require: false
end
group :production do
  gem 'pg', '~> 0.21' # for Heroku deployment
  gem 'rails_12factor'
end


gem 'bulma-rails', '~> 0.6.1'
gem 'simple_form', '~> 3.0'
gem 'devise', '~> 4.7'
gem 'gravatar_image_tag', '~> 1.2'
gem 'carrierwave'
gem 'mimemagic', github: 'mimemagicrb/mimemagic', ref: '01f92d86d15d85cfd0f20dabd025dcbd36a8a60f'

gem 'shrine', '~> 3.3'
gem 'image_processing', '~> 1.12', '>= 1.12.1'