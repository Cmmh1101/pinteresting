# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Run Rails app 

rails server

# Change home page route 
- go to config folder
- open file > routes.rb
get 'home/index'
root 'home#index'
