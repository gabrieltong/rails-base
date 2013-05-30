rails-base
==========

### setup
bundle install
delete index.html
set environments
set database.yml
create database
rake db:migrate
rails generate clearance:install
rails generate clearance:views
rails g cancan:ability
rails generate bootstrap:install less

### others
rails g bootstrap:layout application fluid
rails g bootstrap:layout [LAYOUT_NAME] [*fixed or fluid]
rails g bootstrap:themed [RESOURCE_NAME]