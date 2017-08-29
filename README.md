# README

This project allow to users to list, create, update, delete tasks.

## How it Works

This project has a unique table called todos, this table store ID, name, description, created_at, updated_at. We got a todos controller with every resources to CRUD a todo. The views has developed usign bootstrap.

## Setup
This is a Rails 5 project that uses PostgreSQL as the database. Once you have that installed, download the project by cloning it from Git:
```
$ git clone git@github.com:jeferbc/tasks.git
```
Then, install the dependencies with:

```
$ bundle
```

Create the database and run the migrations by executing:

```
$ rails db:create
$ rails db:schema:load
```

You can seed the database running:

```
$ rails db:seed
```
