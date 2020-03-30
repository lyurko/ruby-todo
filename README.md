# README

This README would normally document whatever steps are necessary to get the
application up and running.

* CRUD - Create, Read, Update, Delete
.new -> creates a new ob, doesn't save to db
.create -> creates and saves to db
.save -> will update
.destroy -> will delete

* Migration - create a table, update, delete

- communicate with database layer through models

- plural controller and table name, singular model name
- instance variable @variable = makes available in the views
rails server -p 3000 -b 127.0.0.1