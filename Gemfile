source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '2.5.1'
gem 'simple_form'
gem 'record_tag_helper', '~> 1.0'
gem 'rails', '~> 5.2.1'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'rails-ujs', '~> 0.1.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0', '>= 5.0.4'
gem 'uglifier', '>= 1.3.0'
gem 'duktape'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'devise', '~> 4.5'
gem 'acts_as_votable', '~> 0.10.0'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'railties'
#gem 'pg'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'bootstrap-sass-extensions', '~> 2.3', '>= 2.3.2.6'

group :development, :test do
 gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
   #gem 'sqlite3'
  
  gem 'web-console', '>= 3.3.0'
end

group :production do
gem 'pg', '~> 1.1', '>= 1.1.3'
gem "activerecord-postgresql-adapter"
gem 'rails_12factor'

end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
