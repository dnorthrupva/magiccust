 source 'https://rubygems.org'

 gem 'rails', '4.2.4'
 gem 'sass-rails', '~> 5.0'
 gem 'uglifier', '>= 1.3.0'
 gem 'coffee-rails', '~> 4.1.0'
 gem 'jquery-rails'
 gem 'turbolinks'
 gem 'bootstrap-sass'
 gem 'bcrypt'
 gem 'figaro', '1.0'
 gem 'mtgextractor', :git => 'git://github.com/JAndritsch/mtgextractor.git'
 
 
 group :production do
   gem 'pg'
   gem 'rails_12factor'
 end
 group :development do
   gem 'sqlite3'
   gem 'pry-rails'
 end

 group :development, :test do
   gem 'rspec-rails', '~> 3.0'
   gem 'factory_girl_rails', '~> 4.0'
 end
 
 group :test do
  gem 'minitest'
  gem 'shoulda-matchers', '~> 3.0'
 end