# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "sinatra"
gem "sinatra-activerecord"
gem 'activerecord', '~> 5.2.0'
gem "rake"

group :development do
    gem 'pry'
    gem 'sqlite3'
    gem 'sinatra-reloader'
end

group :production do
    gem 'pg'    
end