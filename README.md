WWW SQL Designer allows users to create database designs, which can be saved/loaded and exported to SQL scripts. Various databases and languages are supported. Ability to import existing database design.

[[YouTube video](http://www.youtube.com/watch?v=hCQzJx9AKhU)]

# Know more

[[Original project - https://github.com/ondras/wwwsqldesigner](https://github.com/ondras/wwwsqldesigner)]

# Docker build

In docker build you could use environment variables to configure php-mysql backend

* `DATABASE_SERVER`: Server for database
* `DATABASE_USER`: User to access database
* `DATABASE_PASSWORD`: Password for user
* `DATABASE_NAME`: Name of database to create the table to store saved results
* `DATABASE_TABLE`: Table to store saved results
* `DATABASE_ROOT`: User who can access "information_schema" table
* `DATABASE_ROOT_PASSWORD`: Password for root user
