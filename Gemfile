source :gemcutter

gem 'foreman'
gem 'sinatra'
gem 'thin'
gem 'will_paginate'
gem 'data_mapper'
gem 'haml'
gem 'json'
gem 'heroku'
gem 'dm-mysql-adapter'

group :production do
    gem "pg"
    gem "dm-postgres-adapter"
end

group :development, :test do
    #gem "sqlite3"
    #gem 'sqlite3-ruby', :require => 'sqlite3'
    #gem "dm-sqlite-adapter"
    gem 'dm-migrations'
end