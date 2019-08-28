# Edited Le Wagon rails templates

You can quickly generate a rails app with le wagon's config.

All credits to le wagon team for these templates (all written by them), I just edited out the commits and added support for sqlite3 DB.

# Installation with POSTGRESQL Database

## Minimal Installation

Get a minimal rails 5.1+ app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.
Run the next command in the console.

``` bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/DarkDante27/project_templates/master/minimal_postgresql.rb \
  CHANGE_TO_PROJECT_NAME
```

## Installation with Devise

Same as minimal plus a Devise install with a generated User model.

``` bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/DarkDante27/project_templates/master/devise_postgresql.rb \
  CHANGE_TO_PROJECT_NAME
```
