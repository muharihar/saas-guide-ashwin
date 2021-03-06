source 'https://rubygems.org'
ruby "2.2.2"

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

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

#Devise gem
gem "devise"

#Print ruby objects with color and indentation
gem "awesome_print"

#Sidekiq for background processing
gem "sidekiq"
#For sending emails in the background
gem "devise-async"

#Web server
gem "puma"

#Bootstrap sass for styling
gem 'bootstrap-sass', '~> 3.3.5'

gem 'rails_12factor', group: :production

#Simple_form
gem 'simple_form'

#Gem stripe for payment processing
gem 'stripe'
#For processing Stripe events
gem 'stripe_event'

#For tenantizing database
gem 'apartment'

#For storing tenant name in sidekiq
gem 'apartment-sidekiq'

#For sending invitations to users
gem 'devise_invitable'

#For "roles" support
gem "rolify"

#For authorization
gem 'cancancan'


#For fetching weather
gem 'forecast_io'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  #Ultrahook for forwarding stripe events
  gem 'ultrahook'

  #Preview email in the browser instead of sending
  gem "letter_opener"
end

