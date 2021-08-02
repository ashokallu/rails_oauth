source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Docile treats the methods of a given ruby object as a DSL (domain specific language) within a given block. Killer feature: you can also reference methods, instance variables, and local variables from the original (non-DSL) context within the block. Docile releases follow Semantic Versioning as defined at semver.org.
gem 'docile'
# Easy multi-level DSLs, built on top of Docile
gem 'dsl_maker'
gem 'attr_extras' # Takes some boilerplate out of Ruby with methods like attr_initialize.
gem 'takes_macro' # A faster implementation of `pattr_initialize` from the attr_extras gem
# Random name generator for user names
gem 'haikunator' # Generate memorable random names to use in your apps or anywhere else.
gem 'amazing_print' # Great Ruby debugging companion: pretty print Ruby objects to visualize their structure. Supports custom object formatting via plugins
gem 'semantic_logger' # Feature rich logging framework, and replacement for existing Ruby & Rails loggers.
# gem 'rails_semantic_logger' # Feature rich logging framework that replaces the Rails logger.
gem "blazer" # Explore your data with SQL. Easily create charts and dashboards, and share them with your team. # Allows admins to query data
# counter_culture provides turbo-charged counter caches that are kept up-to-date not just on create and destroy, that support multiple levels of indirection through relationships, allow dynamic column names and that avoid deadlocks by updating in the after_commit callback.
gem "counter_culture" # counter_culture provides turbo-charged counter caches that are kept up-to-date
gem "request_store" # RequestStore gives you per-request global storage
gem "rolify" # Very simple Roles library
gem "store_attribute" # ActiveRecord extension which adds typecasting to store accessors.
gem "storext" # Extends ActiveRecord::Store.store_accessor # Add type-casting and other features on top of ActiveRecord::Store.store_accessor
gem 'squint' # Use rails semantics to search keys and values inside PostgreSQL jsonb, json and hstore columns. Compatible with StoreXT attributes.
gem 'escape_utils' # Quickly perform HTML, URL, URI and Javascript escaping/unescaping
gem 'batch-loader' # Powerful tool to avoid N+1 DB or HTTP queries

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Seed Fu is an attempt to once and for all solve the problem of inserting and maintaining seed data in a database. It uses a variety of techniques gathered from various places around the web and combines them to create what is hopefully the most robust seed data system around.
  gem 'seed-fu'
  gem "strong_migrations" # Catch unsafe migrations in development
  gem 'best_debugger' # pry-rails, pry-byebug, better_errors, binding_of_caller all wrapped in one! Our favorite rails tools all in 1 line of code !
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'method_source' # retrieve the sourcecode for a method
  gem 'logster' # UI for viewing logs in Rack
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
