# react_on_rails_sample
hello world rails app (test for react on rails)

## Basic installation for a new Rails App
See below for steps on an existing Rails app

`rails new my-app --webpack=react`

cd into the directory.

Add gem version: gem 'react_on_rails', '11.0.0' # Use the exact 

gem version to match npm version
bundle install

Commit this to git (or else you cannot run the generator unless you pass the option --ignore-warnings).

Run the generator: rails generate react_on_rails:install

Start the app: rails s

Visit http://localhost:3000/hello_world
