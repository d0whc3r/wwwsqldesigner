WWW SQL Designer allows users to create database designs, which can be saved/loaded and exported to SQL scripts. Various databases and languages are supported. Ability to import existing database design.

[YouTube video](http://www.youtube.com/watch?v=hCQzJx9AKhU), [User manual](https://github.com/ondras/wwwsqldesigner/wiki/Manual)

# Know more

[[Original project - https://github.com/ondras/wwwsqldesigner](https://github.com/ondras/wwwsqldesigner)]

# About

Hi and welcome to WWW SQL Designer! This tool allows you to draw and create database schemas (E-R diagrams) directly in browser, without the need for any external programs (flash). You only need JavaScript enabled.
The Designer works perfectly in Chrome, Mozilla (Firefox, Seamonkey), Internet Explorer, MS Edge, Safari and Opera.

Many database features are supported, such as keys, foreign key constraints, comments and indexes. You can either save your design (for further loading & modifications), print it or export as SQL script. It is possible to retrieve (import) schema from existing database.

WWW SQL Designer was created by [Ondrej Zara](http://ondras.zarovi.cz/) and is built atop the [oz.js](http://code.google.com/p/oz-js/) JavaScript module. It is distributed under New BSD license.

If you wish to support this project, <a href='https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3340079'><img src='https://www.paypal.com/en_GB/i/btn/btn_donate_LG.gif' alt='Donate at PayPal' title='Donate at PayPal' /></a> at PayPal!

# Quick Start

## Local Installation:

1. `npm install http-server -g`
2. Run `http-server` in the root of this repo to start a simple http server
3. Visit http://127.0.0.1:8080

# Docker build

Image in: [https://hub.docker.com/r/d0whc3r/wwwsqldesigner/](https://hub.docker.com/r/d0whc3r/wwwsqldesigner/)

In docker build you could use environment variables to configure php-mysql backend

* `DATABASE_SERVER`: Server for database
* `DATABASE_USER`: User to access database
* `DATABASE_PASSWORD`: Password for user
* `DATABASE_NAME`: Name of database to create the table to store saved results
* `DATABASE_TABLE`: Table to store saved results
* `DATABASE_ROOT`: User who can access "information_schema" table
* `DATABASE_ROOT_PASSWORD`: Password for root user
