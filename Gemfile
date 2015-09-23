source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.4' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'sass-rails', '~> 5.0' # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.1.0' # Use CoffeeScript for .coffee assets and views
gem 'bootstrap-sass' #Installs bootstrap framework
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'turbolinks' # Turbolinks makes following links in your web application faster.
gem 'jquery-turbolinks' 
gem 'jbuilder', '~> 2.0' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'devise', '~> 3.5.2'
gem 'paperclip', '~> 4.2'
gem 'aws-sdk', '< 2.0'
gem 'masonry-rails'
gem 'will_paginate', '~> 3.0.5'
gem 'will_paginate-bootstrap'

group :development, :test do
	gem 'sqlite3'# Use sqlite3 as the database for Active Record
end
group :development, :test do
    gem 'byebug' # Call 'byebug' anywhere in the code to stop execution and get a debugger console
end
group :development do  
  	gem 'web-console', '~> 2.0' # Access an IRB console on exception pages or by using <%= console %> in views
  	gem 'spring'  # Spring speeds up development by keeping your application running in the background.
end
group :production do
     gem 'pg'
     gem 'rails_12factor'
end