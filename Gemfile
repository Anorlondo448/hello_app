source 'https://rubygems.org'

# Specify Ruby version
ruby '3.2.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 7.1.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.6.0'
# Use Puma as the app server
gem 'puma', '~> 6.0'
# Use SCSS for stylesheets
gem 'sassc-rails', '~> 2.1'
# Use JavaScript with ESM import maps
gem 'importmap-rails'
# Hotwire's SPA-like page accelerator
gem 'turbo-rails'
# Hotwire's modest JavaScript framework
gem 'stimulus-rails'
# Use Terser as compressor for JavaScript assets
gem 'terser'
# Build JSON APIs with ease
gem 'jbuilder', '~> 2.11'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 5.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails', '~> 6.0'
end

group :development do
  # Use console on exceptions pages
  gem 'web-console', '~> 4.2'
  # Add speed badges to your browser
  gem 'rack-mini-profiler', '~> 3.0'
  # Speed up commands on slow machines / big apps
  gem 'spring'
end

group :test do
  # Use system testing
  gem 'capybara', '~> 3.39'
  gem 'selenium-webdriver'
end
