# Awesome Ruby

A collection of awesome Ruby libraries, tools, frameworks and software :gem:

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php), [awesome-python](https://github.com/vinta/awesome-python), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) and [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks).

Contributions are always welcome! The idea is to build a categorized community-driven collection.

* [Awesome Ruby](#awesome-ruby)
  * [Style Guide](#style-guide)
  * [Package Management](#package-management)
  * [Environment Management](#environment-management)
  * [Documentation](#documentation)
  * [Testing](#testing)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
  * [Database Drivers](#database-drivers)
  * [ORM](#orm)
  * [HTTP](#http)
  * [API Builder](#api-builder)
  * [CLI](#cli)
  * [Authentication](#authentication)
  * [OAuth](#oauth)
  * [Authorization](#authorization)
  * [Queue](#queue)
  * [Template Engine](#template-engine)
  * [Search](#search)
  * [Internationalization](#internationalization)
  * [Geolocation](#geolocation)
  * [Caching](#caching)
  * [Email](#email)
  * [Form Builder](#forms)
  * [Imagery](#imagery)
  * [Video](#video)
  * [WebSocket](#websocket)
  * [HTML Parsing](#html-parsing)
  * [Processes and Threads](#processes-and-threads)
  * [Concurrency](#concurrency)
  * [Error Handling and Monitoring](#error-handling-and-monitoring)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Debugging Tools](#debugging-tools)
  * [Third-party APIs](#third-party-apis)
  * [CMS](#cms)
  * [Admin Interface](#admin-interface)
  * [Static Site Generation](#static-site-generation)
  * [Forum Engine](#forum-engine)
  * [E-Commerce](#e-commerce)
  * [Analytics](#analytics)
  * [DevOps Tools](#devops-tools)
  * [GUI](#gui)
  * [Game Development](#game-development)
  * [Robotics](#robotics)
  * [Misc](#misc)

## Style Guide

* [Ruby style guide](https://github.com/bbatsov/ruby-style-guide) - Community-driven Ruby coding style
* [Rails style guide](https://github.com/bbatsov/rails-style-guide) - Community-driven Rails best practices and style for Rails 3 and 4

## Package Management

* [RubyGems](https://rubygems.org) - Community's gem hosting service
* [Bundler](http://bundler.io/) - Manage your application's gem dependencies with less pain

## Environment Management
* [rbenv](https://github.com/sstephenson/rbenv) — Use rbenv to pick a Ruby version for your application and guarantee that your development environment matches production
* [RVM](https://rvm.io) — RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems
* [dotenv](https://github.com/bkeepers/dotenv)

## Documentation

* [RDoc](https://github.com/rdoc/rdoc) - RDoc produces HTML and command-line documentation for Ruby projects
* [YARD](http://yardoc.org) - YARD enables the user to generate consistent, usable documentation that can be exported to a number of formats very easily

## Testing

* [RSpec](https://github.com/rspec/rspec) - Behaviour Driven Development for Ruby
* [minitest](https://github.com/seattlerb/minitest) - minitest provides a complete suite of testing facilities supporting TDD, BDD, mocking, and benchmarking
* [Test::Unit](http://test-unit.github.io) - Test::Unit is a xUnit family unit testing framework for Ruby
* [Cucumber](https://github.com/cucumber/cucumber) - BDD that talks to domain experts first and code second
* [Capybara](http://jnicklas.github.io/capybara) - Acceptance test framework for web applications
* [Appraisal](https://github.com/thoughtbot/appraisal) - Appraisal integrates with bundler and rake to test your library against different versions of dependencies

## Web Frameworks

* [Ruby on Rails](http://rubyonrails.org)
* [Sinatra](http://www.sinatrarb.com)
* [Padrino](http://www.padrinorb.com)
* [Lotus](http://lotusrb.org)

## Web Servers

* [Rack](http://rack.github.io) - A Ruby Webserver Interface
* [Unicorn](http://unicorn.bogomips.org) - Rack HTTP server for fast clients and Unix
* [Thin](http://code.macournoyer.com/thin) - Tiny, fast & funny HTTP server
* [Puma](https://github.com/puma/puma) - A modern, concurrent web server for Ruby

## Database Drivers

* [ruby-pg](https://bitbucket.org/ged/ruby-pg)
* [mysql2](https://github.com/brianmario/mysql2)
* [SQLite3](https://github.com/sparklemotion/sqlite3-ruby)
* [redis-rb](https://github.com/redis/redis-rb) - A Ruby client that tries to match Redis' API one-to-one, while still providing an idiomatic interface

## ORM

* [ActiveRecord](https://github.com/rails/rails/tree/master/activerecord)
* [Sequel](https://github.com/jeremyevans/sequel) - Sequel is a simple, flexible, and powerful SQL database access toolkit for Ruby
* [Mongoid](http://mongoid.org/en/mongoid/index.html)

## Http

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions
* [httparty](https://github.com/jnunemaker/httparty) 
* [Faraday](https://github.com/lostisland/faraday)

## API Builder

* [Grape](http://intridea.github.io/grape) - An opinionated micro-framework for creating REST-like APIs in Ruby
* [Rails::API](https://github.com/rails-api/rails-api)
* [jbuilder](https://github.com/rails/jbuilder) - Create JSON structures via a Builder-style DSL
* [rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support

## CLI

* [Thor](http://whatisthor.com) - A toolkit for building powerful command-line interfaces
* [Commander](https://github.com/visionmedia/commander) - The complete solution for Ruby command-line executables
* [Slop](https://github.com/leejarvis/slop) - Simple Lightweight Option Parsing

## Authentication

* [Devise](https://github.com/plataformatec/devise)
* [Authlogic](https://github.com/binarylogic/authlogic)
* [OmniAuth](https://github.com/intridea/omniauth)
* [Sorcery](https://github.com/NoamB/sorcery)

## OAuth

* [OAuth2](https://github.com/intridea/oauth2) - A Ruby wrapper for the OAuth 2.0 protocol
* [Doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) - An OAuth2 provider for Rails

## Authorization

* [CanCanCan](https://github.com/CanCanCommunity/cancancan)
* [Pundit](https://github.com/elabs/pundit)

## Queue

* [Resque](https://github.com/resque/resque) — A Redis-backed Ruby library for creating background jobs
* [Sidekiq](http://sidekiq.org) — A full-featured background processing framework for Ruby. It aims to be simple to integrate with any modern Rails application and much higher performance than other existing solutions.
* [Delayed::Job](https://github.com/tobi/delayed_job) — Database backed asynchronous priority queue

## Template Engine

* [Tilt](https://github.com/rtomayko/tilt) - Generic interface to multiple Ruby template engines
* [Haml](https://github.com/haml/haml) - HTML Abstraction Markup Language
* [Slim](https://github.com/slim-template/slim)
* [Liquid](https://github.com/Shopify/liquid)

## Search

* [Thinking Sphinx](https://github.com/pat/thinking-sphinx) - A library for connecting ActiveRecord to the Sphinx full-text search tool
* [elasticsearch-ruby](https://github.com/elasticsearch/elasticsearch-ruby)
* [Searchkick](https://github.com/ankane/searchkick)

## Internationalization

* [i18n](https://github.com/svenfuchs/i18n) - Ruby Internationalization and localization solution
* [i18n-tasks](https://github.com/glebm/i18n-tasks) - Manage missing and unused translations with the awesome power of static analysis.

## Geolocation

* [Geocoder](https://github.com/alexreisner/geocoder)
* [Geokit](https://github.com/geokit/geokit)

## Caching

* [Dalli](https://github.com/mperham/dalli) - A high performance pure Ruby client for accessing memcached servers

## Email

* [Mail](https://github.com/mikel/mail)
* [Pony](https://github.com/benprew/pony)

## Form Builder

* [Simple Form](https://github.com/plataformatec/simple_form)
* [Formtastic](https://github.com/justinfrench/formtastic)

## Imagery

* [MiniMagick](https://github.com/minimagick/minimagick) - A ruby wrapper for ImageMagick or GraphicsMagick command line
* [RMagick](https://github.com/rmagick/rmagick) - RMagick is an interface between Ruby and ImageMagick

## Video

* [Streamio FFMPEG](https://github.com/streamio/streamio-ffmpeg) - Simple yet powerful wrapper around the ffmpeg command for reading metadata and transcoding movies

## WebSocket

* [Faye](http://faye.jcoglan.com/ruby.html)

## HTML Parsing

* [Nokogiri](http://nokogiri.org)

## Processes and Threads

* [Parallel](https://github.com/grosser/parallel)

## Concurrency

* [EventMachine](https://github.com/eventmachine/eventmachine)
* [Celluloid](http://celluloid.io) - Actor-based concurrent object framework for Ruby

## Error Handling and Monitoring

* [Exception Notification](https://github.com/smartinez87/exception_notification) - A set of notifiers for sending notifications when errors occur in a Rack/Rails application
* [Errbit](http://errbit.github.io/errbit) - The open source, self-hosted error catcher
* [Airbrake](https://github.com/airbrake/airbrake) - The official Airbrake library for Ruby on Rails (and other Rack based frameworks)

## Code Analysis and Metrics

* [SimpleCov](https://github.com/colszowka/simplecov) - Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites
* [Rubocop](https://github.com/bbatsov/rubocop)
* [rails_best_practices](https://github.com/railsbp/rails_best_practices) - A code metric tool for rails projects

## Debugging Tools

* [debugger](https://github.com/cldwalker/debugger)
* [Byebug](https://github.com/deivid-rodriguez/byebug) - A simple to use, feature rich debugger for Ruby 2

## Third-party APIs

* [Octokit](http://octokit.github.io/octokit.rb) - Ruby toolkit for the GitHub API
* [fb_graph](https://github.com/nov/fb_graph) - A full-stack Facebook Graph API wrapper
* [twitter](https://github.com/sferik/twitter) - A Ruby interface to the Twitter API
  * [t](https://github.com/sferik/t) - A command-line power tool for Twitter
* [tweetstream](https://github.com/tweetstream/tweetstream) - A simple library for consuming Twitter's Streaming API
* [instagram-ruby-gem](https://github.com/Instagram/instagram-ruby-gem) - The official gem for the Instagram REST and Search APIs
* [soundcloud-ruby](https://github.com/soundcloud/soundcloud-ruby) - Official SoundCloud API Wrapper for Ruby
* [linkedin](https://github.com/hexgnu/linkedin) - Provides an easy-to-use wrapper for LinkedIn's REST APIs
* [youtube_it](https://github.com/kylejginavan/youtube_it) - An object-oriented Ruby wrapper for the YouTube GData API
* [ruby-trello](https://github.com/jeremytregunna/ruby-trello) - Implementation of the Trello API for Ruby
* [hipchat-rb](https://github.com/hipchat/hipchat-rb) - HipChat HTTP API Wrapper in Ruby with Capistrano hooks

## CMS

* [Refinery CMS](http://refinerycms.com)
* [Radiant](http://radiantcms.org)
* [LocomotiveCMS](http://www.locomotivecms.com)

## Admin Interface

* [ActiveAdmin](http://activeadmin.info)
* [RailsAdmin](https://github.com/sferik/rails_admin)

## Static Site Generation

* [Jekyll](http://jekyllrb.com)
* [Middleman](http://middlemanapp.com)

## Forum Engine

* [Forem](https://github.com/radar/forem)

## E-Commerce

* [Active Merchant](https://github.com/Shopify/active_merchant) - A simple payment abstraction library extracted from Shopify
* [Spree](http://spreecommerce.com)
* [ROR Ecommerce](http://www.ror-e.com)

## Analytics

* [Gabba](https://github.com/hybridgroup/gabba)
* [Ahoy](https://github.com/ankane/ahoy) - A solid foundation to track visits and events in Ruby, JavaScript, and native apps

## DevOps Tools

* [Capistrano](http://capistranorb.com)
* [Backup](https://github.com/meskyanichi/backup)
* [Puppet](https://github.com/puppetlabs/puppet)

## GUI

* [Shoes](http://shoesrb.com)

## Game Development

* [Gosu](http://www.libgosu.org)

## Mobile Development

* [RubyMotion](http://www.rubymotion.com) - A revolutionary toolchain that lets you quickly develop and test native iOS and OS X applications for iPhone, iPad and Mac
* [Ruboto](http://ruboto.org) - A platform for developing full stand-alone apps for Android using the Ruby language and libraries

## Robotics

* [Artoo](http://artoo.io)

## Misc

* [Betty](https://github.com/pickhardt/betty) - Friendly English-like interface for your command line. Don't remember a command? Ask Betty