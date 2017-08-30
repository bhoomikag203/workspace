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
$bundle install --without production

next ,migrate the database:

$rails db:migrate

finally ,run the test suite to verfy that everything is working correctly

$rails test

if the text suite passes ,you'll be ready to run the app in local sever

$rails server
