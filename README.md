# Quicksb2

This is a simple config to use sb-admin2 from startbootstrap in Rails projects.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'bootstrap-sass', '~> 3.3.6'
gem 'font-awesome-sass', '~> 4.5.0'
gem 'quicksb2'
```

And then execute:

    $ bundle


Import bootstrap styles in app/assets/stylesheets/application.scss. Obs: If it's not .scss extension, please change it.

```ruby
@import "bootstrap-sprockets";
@import "bootstrap";
@import "metisMenu.min";
@import "timeline";
@import "sb-admin-2";
@import "morris";
@import "toggle";
@import "font-awesome-sprockets";
@import "font-awesome";
```
And into app/assets/javascripts/application.js

```ruby
//= require jquery2
//= require jquery_ujs
//= require bootstrap-sprockets
//= require metisMenu
//= require sb-admin-2
```

