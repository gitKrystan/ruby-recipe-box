# Recipe Box

#### By Krystan Menne and Jeff Seymour

## Description
Ruby web app that stores recipes, including ingredients and tags.
Practicing many-to-many relationships with ActiveRecord.

## Technologies Used
HTML, CSS, Ruby, ActiveRecord, PostgreSQL, rspec, capybara, sinatra.

## Installation
Clone repository.  
Run Postgres.  
In terminal:

```
bundle install  
rake db:create
rake db:migrate  
rake db:test:prepare
ruby app.rb
```

### License

Copyright (c) 2016 Krystan Menne and Jeff Seymour

This software is licensed under the MIT license.
