source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'


# Use sqlite3 as the database for Active Record
gem 'sqlite3'
gem 'nokogiri'
gem 'kaminari'

# Use SCSS for stylesheets

gem 'simple_form'
gem 'less-rails' 
gem 'twitter-bootstrap-rails'
gem 'd3-rails'

gem 'whenever', :require => false

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

gem 'libv8'
gem 'execjs'
gem 'therubyracer', :platforms => :ruby



# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

gem 'rails-i18n' # この行を追加(ransackには関係ないけどdate_select用)
gem 'ransack'   # この行を追加


group :production do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'mysql2'
end


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development do
  gem 'capistrano-rails'
  gem 'capistrano', '~> 3.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv' 
end


group :test, :development do
  gem "pry-rails"
  gem "pry-doc"
  gem "pry-stack_explorer"
  gem "pry-byebug"
  gem "hirb"
  gem "hirb-unicode"
  gem "tapp"
  gem "awesome_print"

  gem "better_errors"
  gem "binding_of_caller"
  gem "quiet_assets"
  gem "annotate", github: "ctran/annotate_models"
  gem "timecop"
  gem "colorize_unpermitted_parameters"
  gem "rack-mini-profiler"
  gem "xray-rails"

  gem "rspec", "~> 3.0.0.beta"
  gem "rspec-rails", "~> 3.0.0.beta"
  gem "guard-rspec", require: false
  gem "spring-commands-rspec"
  gem "factory_girl_rails"
  gem "database_rewinder"
  gem "faker"
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
