source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

#Use Unicorn as the app server
gem 'unicorn'

group :development do
  # Гем, который добавляет специфические для Rails таски, такие как прогон миграций и компиляция ассетов
  gem 'capistrano-rails'
  # Гем, добавляющий возможности bundle к capistrano
  gem 'capistrano-bundler'
  # Добавление поддержки Rbenv (менеджера версий для Ruby)
  gem 'capistrano-rbenv'
  # Интеграция пумы и капистрано
  gem 'capistrano3-puma'
  #secret-key
  gem 'capistrano-secrets-yml'
end

group :production do 
  # Puma - это Ruby/Rack сервер, который будет получать запросы из Nginx и направлять их в Rails, эдакое связующее звено
  gem 'puma'
end

group :development, :test do
  gem 'pry', '~> 0.9'
  gem 'pry-nav', '~> 0.2'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

