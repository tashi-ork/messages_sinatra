# Gemfile

source 'https://rubygems.org'
ruby "2.2.2"

gem 'sinatra'
gem 'sinatra-activerecord' 
gem 'sinatra-flash'
gem 'sinatra-redirect-with-flash'
gem 'rake'

group :development, :test do
	gem 'sqlite3'
	gem 'tux'
end

group :test do
	gem 'rspec'
	gem 'rack-test'
end

group :production do
	gem 'pg'
end

