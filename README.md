Last login: Thu Jun  7 16:32:50 on ttys007
adam.pann:~ $ cd
.Trash/           .cups/            .rvm/             Applications/     Downloads/        Music/            RubymineProjects/ braavos-web/
.bash_sessions/   .emacs.d/         .ssh/             Desktop/          Library/          Pictures/         berlioz-example/  homeone/
.bundle/          .gem/             .subversion/      Documents/        Movies/           Public/           braavos/          practice-rails/
adam.pann:~ $ cd practice-rails/
adam.pann:~/practice-rails $ cd enviroment/
adam.pann:~/practice-rails/enviroment $
Display all 2197 possibilities? (y or n)
adam.pann:~/practice-rails/enviroment $ cd
hello_app/ toy_app/
adam.pann:~/practice-rails/enviroment $ cd toy_app/
adam.pann:~/practice-rails/enviroment/toy_app (master) $ ls
Gemfile		README.md	app		config		db		log		public		tmp
Gemfile.lock	Rakefile	bin		config.ru	lib		package.json	test		vendor
adam.pann:~/practice-rails/enviroment/toy_app (master) $ cd app
adam.pann:~/practice-rails/enviroment/toy_app/app (master) $ ls
assets		channels	controllers	helpers		jobs		mailers		models		views
adam.pann:~/practice-rails/enviroment/toy_app/app (master) $ em
adam.pann:~/practice-rails/enviroment/toy_app/app (master) $ ls
assets		channels	controllers	helpers		jobs		mailers		models		views
adam.pann:~/practice-rails/enviroment/toy_app/app (master) $ cd ..
adam.pann:~/practice-rails/enviroment/toy_app (master) $ em config/
application.rb  cable.yml       environment.rb  initializers/   puma.rb         secrets.yml
boot.rb         database.yml    environments/   locales/        routes.rb       spring.rb
adam.pann:~/practice-rails/enviroment/toy_app (master) $ em config/
application.rb  cable.yml       environment.rb  initializers/   puma.rb         secrets.yml
boot.rb         database.yml    environments/   locales/        routes.rb       spring.rb
adam.pann:~/practice-rails/enviroment/toy_app (master) $ em config/routes.rb
adam.pann:~/practice-rails/enviroment/toy_app (master) $ cd ..
adam.pann:~/practice-rails/enviroment $ rails generate scaffold Micropost content:text user_id:integer
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
Usage:
  rails new APP_PATH [options]

Options:
  -r, [--ruby=PATH]                                      # Path to the Ruby binary of your choice
                                                         # Default: /usr/local/Cellar/ruby/2.5.1/bin/ruby
  -m, [--template=TEMPLATE]                              # Path to some application template (can be a filesystem path or URL)
  -d, [--database=DATABASE]                              # Preconfigure for selected database (options: mysql/postgresql/sqlite3/oracle/frontbase/ibm_db/sqlserver/jdbcmysql/jdbcsqlite3/jdbcpostgresql/jdbc)
                                                         # Default: sqlite3
      [--skip-yarn], [--no-skip-yarn]                    # Don't use Yarn for managing JavaScript dependencies
      [--skip-gemfile], [--no-skip-gemfile]              # Don't create a Gemfile
  -G, [--skip-git], [--no-skip-git]                      # Skip .gitignore file
      [--skip-keeps], [--no-skip-keeps]                  # Skip source control .keep files
  -M, [--skip-action-mailer], [--no-skip-action-mailer]  # Skip Action Mailer files
  -O, [--skip-active-record], [--no-skip-active-record]  # Skip Active Record files
  -P, [--skip-puma], [--no-skip-puma]                    # Skip Puma related files
  -C, [--skip-action-cable], [--no-skip-action-cable]    # Skip Action Cable files
  -S, [--skip-sprockets], [--no-skip-sprockets]          # Skip Sprockets files
      [--skip-spring], [--no-skip-spring]                # Don't install Spring application preloader
      [--skip-listen], [--no-skip-listen]                # Don't generate configuration that depends on the listen gem
      [--skip-coffee], [--no-skip-coffee]                # Don't use CoffeeScript
  -J, [--skip-javascript], [--no-skip-javascript]        # Skip JavaScript files
      [--skip-turbolinks], [--no-skip-turbolinks]        # Skip turbolinks gem
  -T, [--skip-test], [--no-skip-test]                    # Skip test files
      [--skip-system-test], [--no-skip-system-test]      # Skip system test files
      [--dev], [--no-dev]                                # Setup the application with Gemfile pointing to your Rails checkout
      [--edge], [--no-edge]                              # Setup the application with Gemfile pointing to Rails repository
      [--rc=RC]                                          # Path to file containing extra configuration options for rails command
      [--no-rc], [--no-no-rc]                            # Skip loading of extra configuration options from .railsrc file
      [--api], [--no-api]                                # Preconfigure smaller stack for API only apps
  -B, [--skip-bundle], [--no-skip-bundle]                # Don't run bundle install
      [--webpack=WEBPACK]                                # Preconfigure for app-like JavaScript with Webpack (options: react/vue/angular)

Runtime options:
  -f, [--force]                    # Overwrite files that already exist
  -p, [--pretend], [--no-pretend]  # Run but do not make any changes
  -q, [--quiet], [--no-quiet]      # Suppress status output
  -s, [--skip], [--no-skip]        # Skip files that already exist

Rails options:
  -h, [--help], [--no-help]        # Show this help message and quit
  -v, [--version], [--no-version]  # Show Rails version number and quit

Description:
    The 'rails new' command creates a new Rails application with a default
    directory structure and configuration at the path you specify.

    You can specify extra command-line arguments to be used every time
    'rails new' runs in the .railsrc configuration file in your home directory.

    Note that the arguments specified in the .railsrc file don't affect the
    defaults values shown above in this help message.

Example:
    rails new ~/Code/Ruby/weblog

    This generates a skeletal Rails installation in ~/Code/Ruby/weblog.
adam.pann:~/practice-rails/enviroment $ ls
hello_app	toy_app
adam.pann:~/practice-rails/enviroment $ cd toy_app/
adam.pann:~/practice-rails/enviroment/toy_app (master) $
adam.pann:~/practice-rails/enviroment/toy_app (master) $ rials generate scaffold Micropost content:text user_id:integer
-bash: rials: command not found
adam.pann:~/practice-rails/enviroment/toy_app (master) $ rails generate scaffold Micropost content:text user_id:integer
Running via Spring preloader in process 77780
      invoke  active_record
      create    db/migrate/20180608153000_create_microposts.rb
      create    app/models/micropost.rb
      invoke    test_unit
      create      test/models/micropost_test.rb
      create      test/fixtures/microposts.yml
      invoke  resource_route
       route    resources :microposts
      invoke  scaffold_controller
      create    app/controllers/microposts_controller.rb
      invoke    erb
      create      app/views/microposts
      create      app/views/microposts/index.html.erb
      create      app/views/microposts/edit.html.erb
      create      app/views/microposts/show.html.erb
      create      app/views/microposts/new.html.erb
      create      app/views/microposts/_form.html.erb
      invoke    test_unit
      create      test/controllers/microposts_controller_test.rb
      invoke    helper
      create      app/helpers/microposts_helper.rb
      invoke      test_unit
      invoke    jbuilder
      create      app/views/microposts/index.json.jbuilder
      create      app/views/microposts/show.json.jbuilder
      create      app/views/microposts/_micropost.json.jbuilder
      invoke  test_unit
      create    test/system/microposts_test.rb
      invoke  assets
      invoke    coffee
      create      app/assets/javascripts/microposts.coffee
      invoke    scss
      create      app/assets/stylesheets/microposts.scss
      invoke  scss
   identical    app/assets/stylesheets/scaffolds.scss
adam.pann:~/practice-rails/enviroment/toy_app (master) $ rails db:migrate
== 20180608153000 CreateMicroposts: migrating =================================
-- create_table(:microposts)
   -> 0.0016s
== 20180608153000 CreateMicroposts: migrated (0.0017s) ========================

adam.pann:~/practice-rails/enviroment/toy_app (master) $
adam.pann:~/practice-rails/enviroment/toy_app (master) $ rails server
=> Booting Puma
=> Rails 5.1.6 application starting in development
=> Run `rails server -h` for more startup options
A server is already running. Check /Users/adam.pann/practice-rails/enviroment/toy_app/tmp/pids/server.pid.
Exiting
adam.pann:~/practice-rails/enviroment/toy_app (master) $ gs
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   config/routes.rb

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	app/assets/javascripts/microposts.coffee
	app/assets/javascripts/users.coffee
	app/assets/stylesheets/microposts.scss
	app/assets/stylesheets/scaffolds.scss
	app/assets/stylesheets/users.scss
	app/controllers/microposts_controller.rb
	app/controllers/users_controller.rb
	app/helpers/microposts_helper.rb
	app/helpers/users_helper.rb
	app/models/micropost.rb
	app/models/user.rb
	app/views/microposts/
	app/views/users/
	db/migrate/
	db/schema.rb
	test/controllers/microposts_controller_test.rb
	test/controllers/users_controller_test.rb
	test/fixtures/microposts.yml
	test/fixtures/users.yml
	test/models/micropost_test.rb
	test/models/user_test.rb
	test/system/microposts_test.rb
	test/system/users_test.rb

no changes added to commit (use "git add" and/or "git commit -a")
adam.pann:~/practice-rails/enviroment/toy_app (master) $ git add -A
adam.pann:~/practice-rails/enviroment/toy_app (master) $ git commit -m "finished toy app"
[master c8b9e1d] finished toy app
 39 files changed, 626 insertions(+)
 create mode 100644 app/assets/javascripts/microposts.coffee
 create mode 100644 app/assets/javascripts/users.coffee
 create mode 100644 app/assets/stylesheets/microposts.scss
 create mode 100644 app/assets/stylesheets/scaffolds.scss
 create mode 100644 app/assets/stylesheets/users.scss
 create mode 100644 app/controllers/microposts_controller.rb
 create mode 100644 app/controllers/users_controller.rb
 create mode 100644 app/helpers/microposts_helper.rb
 create mode 100644 app/helpers/users_helper.rb
 create mode 100644 app/models/micropost.rb
 create mode 100644 app/models/user.rb
 create mode 100644 app/views/microposts/_form.html.erb
 create mode 100644 app/views/microposts/_micropost.json.jbuilder
 create mode 100644 app/views/microposts/edit.html.erb
 create mode 100644 app/views/microposts/index.html.erb
 create mode 100644 app/views/microposts/index.json.jbuilder
 create mode 100644 app/views/microposts/new.html.erb
 create mode 100644 app/views/microposts/show.html.erb
 create mode 100644 app/views/microposts/show.json.jbuilder
 create mode 100644 app/views/users/_form.html.erb
 create mode 100644 app/views/users/_user.json.jbuilder
 create mode 100644 app/views/users/edit.html.erb
 create mode 100644 app/views/users/index.html.erb
 create mode 100644 app/views/users/index.json.jbuilder
 create mode 100644 app/views/users/new.html.erb
 create mode 100644 app/views/users/show.html.erb
 create mode 100644 app/views/users/show.json.jbuilder
 create mode 100644 db/migrate/20180607235335_create_users.rb
 create mode 100644 db/migrate/20180608153000_create_microposts.rb
 create mode 100644 db/schema.rb
 create mode 100644 test/controllers/microposts_controller_test.rb
 create mode 100644 test/controllers/users_controller_test.rb
 create mode 100644 test/fixtures/microposts.yml
 create mode 100644 test/fixtures/users.yml
 create mode 100644 test/models/micropost_test.rb
 create mode 100644 test/models/user_test.rb
 create mode 100644 test/system/microposts_test.rb
 create mode 100644 test/system/users_test.rb
adam.pann:~/practice-rails/enviroment/toy_app (master) $ git push
Enter passphrase for key '/Users/adam.pann/.ssh/id_rsa':
Counting objects: 58, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (55/55), done.
Writing objects: 100% (58/58), 8.84 KiB | 2.21 MiB/s, done.
Total 58 (delta 11), reused 0 (delta 0)
remote: Resolving deltas: 100% (11/11), completed with 4 local objects.
To github.com:adampann/toy_app.git
   934e3b3..c8b9e1d  master -> master
adam.pann:~/practice-rails/enviroment/toy_app (master) $ cd ..
adam.pann:~/practice-rails/enviroment $ rails _5.1.4_ new sample_app
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
      create
      create  README.md
      create  Rakefile
      create  config.ru
      create  .gitignore
      create  Gemfile
         run  git init from "."
Initialized empty Git repository in /Users/adam.pann/practice-rails/enviroment/sample_app/.git/
      create  app
      create  app/assets/config/manifest.js
      create  app/assets/javascripts/application.js
      create  app/assets/javascripts/cable.js
      create  app/assets/stylesheets/application.css
      create  app/channels/application_cable/channel.rb
      create  app/channels/application_cable/connection.rb
      create  app/controllers/application_controller.rb
      create  app/helpers/application_helper.rb
      create  app/jobs/application_job.rb
      create  app/mailers/application_mailer.rb
      create  app/models/application_record.rb
      create  app/views/layouts/application.html.erb
      create  app/views/layouts/mailer.html.erb
      create  app/views/layouts/mailer.text.erb
      create  app/assets/images/.keep
      create  app/assets/javascripts/channels
      create  app/assets/javascripts/channels/.keep
      create  app/controllers/concerns/.keep
      create  app/models/concerns/.keep
      create  bin
      create  bin/bundle
      create  bin/rails
      create  bin/rake
      create  bin/setup
      create  bin/update
      create  bin/yarn
      create  config
      create  config/routes.rb
      create  config/application.rb
      create  config/environment.rb
      create  config/secrets.yml
      create  config/cable.yml
      create  config/puma.rb
      create  config/spring.rb
      create  config/environments
      create  config/environments/development.rb
      create  config/environments/production.rb
      create  config/environments/test.rb
      create  config/initializers
      create  config/initializers/application_controller_renderer.rb
      create  config/initializers/assets.rb
      create  config/initializers/backtrace_silencers.rb
      create  config/initializers/cookies_serializer.rb
      create  config/initializers/cors.rb
      create  config/initializers/filter_parameter_logging.rb
      create  config/initializers/inflections.rb
      create  config/initializers/mime_types.rb
      create  config/initializers/new_framework_defaults_5_1.rb
      create  config/initializers/wrap_parameters.rb
      create  config/locales
      create  config/locales/en.yml
      create  config/boot.rb
      create  config/database.yml
      create  db
      create  db/seeds.rb
      create  lib
      create  lib/tasks
      create  lib/tasks/.keep
      create  lib/assets
      create  lib/assets/.keep
      create  log
      create  log/.keep
      create  public
      create  public/404.html
      create  public/422.html
      create  public/500.html
      create  public/apple-touch-icon-precomposed.png
      create  public/apple-touch-icon.png
      create  public/favicon.ico
      create  public/robots.txt
      create  test/fixtures
      create  test/fixtures/.keep
      create  test/fixtures/files
      create  test/fixtures/files/.keep
      create  test/controllers
      create  test/controllers/.keep
      create  test/mailers
      create  test/mailers/.keep
      create  test/models
      create  test/models/.keep
      create  test/helpers
      create  test/helpers/.keep
      create  test/integration
      create  test/integration/.keep
      create  test/test_helper.rb
      create  test/system
      create  test/system/.keep
      create  test/application_system_test_case.rb
      create  tmp
      create  tmp/.keep
      create  tmp/cache
      create  tmp/cache/assets
      create  vendor
      create  vendor/.keep
      create  package.json
      remove  config/initializers/cors.rb
      remove  config/initializers/new_framework_defaults_5_1.rb
         run  bundle install
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
Fetching gem metadata from https://rubygems.org/...............
Fetching gem metadata from https://rubygems.org/..
Resolving dependencies.....
Error loading RubyGems plugin "/Users/adam.pann/.rvm/gems/ruby-2.4.3@global/gems/executable-hooks-1.4.2/lib/rubygems_plugin.rb": cannot load such file -- executable-hooks/wrapper (LoadError)
Error loading RubyGems plugin "/Users/adam.pann/.rvm/gems/ruby-2.4.3@global/gems/gem-wrappers-1.4.0/lib/rubygems_plugin.rb": cannot load such file -- gem-wrappers (LoadError)
Using rake 12.3.1
Using concurrent-ruby 1.0.5
Using i18n 1.0.1
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.1.6
Using builder 3.2.3
Using erubi 1.7.1
Using mini_portile2 2.3.0
Using nokogiri 1.8.2
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.2
Using rails-html-sanitizer 1.0.4
Using actionview 5.1.6
Using rack 2.0.5
Using rack-test 1.0.0
Using actionpack 5.1.6
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.6.5
Using actioncable 5.1.6
Using globalid 0.4.1
Using activejob 5.1.6
Using mini_mime 1.0.0
Using mail 2.7.0
Using actionmailer 5.1.6
Using activemodel 5.1.6
Using arel 8.0.0
Using activerecord 5.1.6
Using public_suffix 3.0.2
Using addressable 2.5.2
Using bindex 0.5.0
Using bundler 1.16.2
Using byebug 10.0.2
Using xpath 3.1.0
Using capybara 2.18.0
Using ffi 1.9.25
Using childprocess 0.9.0
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.0
Using thor 0.20.0
Using railties 5.1.6
Using coffee-rails 4.2.2
Using multi_json 1.13.1
Using jbuilder 2.7.0
Using rb-fsevent 0.10.3
Using rb-inotify 0.9.10
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.11.4
Using sprockets 3.7.1
Using sprockets-rails 3.2.1
Using rails 5.1.6
Using rubyzip 1.2.1
Using sass-listen 4.0.0
Using sass 3.5.6
Using tilt 2.0.8
Using sass-rails 5.0.7
Using selenium-webdriver 3.12.0
Using spring 2.0.2
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.1.0
Using turbolinks 5.1.1
Using uglifier 4.1.11
Using web-console 3.6.2
Bundle complete! 16 Gemfile dependencies, 70 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
         run  bundle exec spring binstub --all
* bin/rake: spring inserted
* bin/rails: spring inserted
adam.pann:~/practice-rails/enviroment $ cd sample_app/
adam.pann:~/practice-rails/enviroment/sample_app $ bundle install --without production
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
Using rake 12.3.1
Using concurrent-ruby 1.0.5
Using i18n 1.0.1
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.1.6
Using builder 3.2.3
Using erubi 1.7.1
Using mini_portile2 2.3.0
Using nokogiri 1.8.2
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.2
Using rails-html-sanitizer 1.0.4
Using actionview 5.1.6
Using rack 2.0.5
Using rack-test 1.0.0
Using actionpack 5.1.6
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.6.5
Using actioncable 5.1.6
Using globalid 0.4.1
Using activejob 5.1.6
Using mini_mime 1.0.0
Using mail 2.7.0
Using actionmailer 5.1.6
Using activemodel 5.1.6
Using arel 8.0.0
Using activerecord 5.1.6
Using public_suffix 3.0.2
Using addressable 2.5.2
Using bindex 0.5.0
Using bundler 1.16.2
Using byebug 10.0.2
Using xpath 3.1.0
Using capybara 2.18.0
Using ffi 1.9.25
Using childprocess 0.9.0
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.0
Using thor 0.20.0
Using railties 5.1.6
Using coffee-rails 4.2.2
Using multi_json 1.13.1
Using jbuilder 2.7.0
Using rb-fsevent 0.10.3
Using rb-inotify 0.9.10
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.11.4
Using sprockets 3.7.1
Using sprockets-rails 3.2.1
Using rails 5.1.6
Using rubyzip 1.2.1
Using sass-listen 4.0.0
Using sass 3.5.6
Using tilt 2.0.8
Using sass-rails 5.0.7
Using selenium-webdriver 3.12.0
Using spring 2.0.2
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.1.0
Using turbolinks 5.1.1
Using uglifier 4.1.11
Using web-console 3.6.2
Bundle complete! 16 Gemfile dependencies, 70 gems now installed.
Gems in the group production were not installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
adam.pann:~/practice-rails/enviroment/sample_app $ bundle update
Ignoring executable-hooks-1.4.2 because its extensions are not built. Try: gem pristine executable-hooks --version 1.4.2
Ignoring gem-wrappers-1.4.0 because its extensions are not built. Try: gem pristine gem-wrappers --version 1.4.0
The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
Fetching gem metadata from https://rubygems.org/...............
Fetching gem metadata from https://rubygems.org/..
Resolving dependencies.....
Error loading RubyGems plugin "/Users/adam.pann/.rvm/gems/ruby-2.4.3@global/gems/executable-hooks-1.4.2/lib/rubygems_plugin.rb": cannot load such file -- executable-hooks/wrapper (LoadError)
Error loading RubyGems plugin "/Users/adam.pann/.rvm/gems/ruby-2.4.3@global/gems/gem-wrappers-1.4.0/lib/rubygems_plugin.rb": cannot load such file -- gem-wrappers (LoadError)
Using rake 12.3.1
Using concurrent-ruby 1.0.5
Using i18n 1.0.1
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.1.6
Using builder 3.2.3
Using erubi 1.7.1
Using mini_portile2 2.3.0
Using nokogiri 1.8.2
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.2
Using rails-html-sanitizer 1.0.4
Using actionview 5.1.6
Using rack 2.0.5
Using rack-test 1.0.0
Using actionpack 5.1.6
Using nio4r 2.3.1
Using websocket-extensions 0.1.3
Using websocket-driver 0.6.5
Using actioncable 5.1.6
Using globalid 0.4.1
Using activejob 5.1.6
Using mini_mime 1.0.0
Using mail 2.7.0
Using actionmailer 5.1.6
Using activemodel 5.1.6
Using arel 8.0.0
Using activerecord 5.1.6
Using public_suffix 3.0.2
Using addressable 2.5.2
Using bindex 0.5.0
Using bundler 1.16.2
Using byebug 10.0.2
Using xpath 3.1.0
Using capybara 2.18.0
Using ffi 1.9.25
Using childprocess 0.9.0
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.0
Using thor 0.20.0
Using railties 5.1.6
Using coffee-rails 4.2.2
Using multi_json 1.13.1
Using jbuilder 2.7.0
Using rb-fsevent 0.10.3
Using rb-inotify 0.9.10
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.11.4
Using sprockets 3.7.1
Using sprockets-rails 3.2.1
Using rails 5.1.6
Using rubyzip 1.2.1
Using sass-listen 4.0.0
Using sass 3.5.6
Using tilt 2.0.8
Using sass-rails 5.0.7
Using selenium-webdriver 3.12.0
Using spring 2.0.2
Using spring-watcher-listen 2.0.1
Using sqlite3 1.3.13
Using turbolinks-source 5.1.0
Using turbolinks 5.1.1
Using uglifier 4.1.11
Using web-console 3.6.2
Bundle updated!
Gems in the group production were not installed.
adam.pann:~/practice-rails/enviroment/sample_app $ git init
Reinitialized existing Git repository in /Users/adam.pann/practice-rails/enviroment/sample_app/.git/
adam.pann:~/practice-rails/enviroment/sample_app $ git add -A
adam.pann:~/practice-rails/enviroment/sample_app $ git commit -m "Initialize respoitory"
[master (root-commit) 5a9344e] Initialize respoitory
 76 files changed, 1197 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 README.md
 create mode 100644 Rakefile
 create mode 100644 app/assets/config/manifest.js
 create mode 100644 app/assets/images/.keep
 create mode 100644 app/assets/javascripts/application.js
 create mode 100644 app/assets/javascripts/cable.js
 create mode 100644 app/assets/javascripts/channels/.keep
 create mode 100644 app/assets/stylesheets/application.css
 create mode 100644 app/channels/application_cable/channel.rb
 create mode 100644 app/channels/application_cable/connection.rb
 create mode 100644 app/controllers/application_controller.rb
 create mode 100644 app/controllers/concerns/.keep
 create mode 100644 app/helpers/application_helper.rb
 create mode 100644 app/jobs/application_job.rb
 create mode 100644 app/mailers/application_mailer.rb
 create mode 100644 app/models/application_record.rb
 create mode 100644 app/models/concerns/.keep
 create mode 100644 app/views/layouts/application.html.erb
 create mode 100644 app/views/layouts/mailer.html.erb
 create mode 100644 app/views/layouts/mailer.text.erb
 create mode 100755 bin/bundle
 create mode 100755 bin/rails
 create mode 100755 bin/rake
 create mode 100755 bin/setup
 create mode 100755 bin/spring
 create mode 100755 bin/update
 create mode 100755 bin/yarn
 create mode 100644 config.ru
 create mode 100644 config/application.rb
 create mode 100644 config/boot.rb
 create mode 100644 config/cable.yml
 create mode 100644 config/database.yml
 create mode 100644 config/environment.rb
 create mode 100644 config/environments/development.rb
 create mode 100644 config/environments/production.rb
File Edit Options Buffers Tools Help
 1# README
 2
 3This README would normally document whatever steps are necessary to get the
 4application up and running.
 5
 6Things you may want to cover:
 7
 8* Ruby version
 9
10* System dependencies
11
12* Configuration
13
14* Database creation
15
16* Database initialization
17
18* How to run the test suite
19
20* Services (job queues, cache servers, search engines, etc.)
21
22* Deployment instructions
23
24* ...
















-UU-:----F1  README.md      All L1    Git-master  (Fundamental) ----------------------------------------------------------------------------------------------------------------
For information about GNU Emacs and the GNU system, type C-h C-a.# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:
77For information about GNU Emacs and the GNU system, type C-h C-a.# README
678
679This README would normally document whatever steps are necessary to get the
680application up and running.
681
682Things you may want to cover:
683
684* Ruby version
685
686* System dependencies
687
688* Configuration
689
690* Database creation
691
692* Database initialization
693
694* How to run the test suite
695
696* Services (job queues, cache servers, search engines, etc.)
697
698* Deployment instructions
699
700* ...