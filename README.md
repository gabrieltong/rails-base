rails-base
==========

### setup
1. bundle install
1. delete index.html
1. set environments
1. set database.yml
1. create database
1. rake db:migrate
1. rails generate clearance:install
1. rails generate clearance:views
1. rails g cancan:ability
1. rails generate bootstrap:install less

### others
1. rails g bootstrap:layout application fluid
1. rails g bootstrap:layout [LAYOUT_NAME] [*fixed or fluid]
1. rails g bootstrap:themed [RESOURCE_NAME]