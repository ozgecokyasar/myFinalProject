source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rack-cors'
gem 'rails', '~> 5.1.2'
gem 'font-awesome-rails'
gem 'active_model_serializers'
gem 'carrierwave', '~> 1.0'
gem 'lightbox-bootstrap-rails', '5.1.0.1'
gem 'simple_form'
gem 'mini_magick'
gem 'geocoder'
gem 'omniauth-twitter'
gem 'gmaps4rails'
gem 'geocomplete_rails'
gem 'underscore-rails'
gem 'jwt'
 gem 'filterrific'
 gem 'country_select'
# Use postgresql as the database for Active Record

# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass', '~> 3.3.6'
gem "table_print"
gem 'fog'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
gem "twitter-bootstrap-rails"
gem 'materialize-sass'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'pg', '~> 0.21'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'bcrypt', '~> 3.1.7'
gem 'faker', github:'stympy/faker'
gem 'cancancan', '~> 2.0'
gem 'bootstrap_form'
gem 'jquery-rails'
gem 'bcrypt-ruby'
gem 'rails_12factor'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'awesome_print'
gem 'interactive_editor'
gem 'hirb'

end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
