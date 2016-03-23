Rails Devise
================

This application was generated with the [rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) gem
provided by the [RailsApps Project](http://railsapps.github.io/).

Rails Composer is supported by developers who purchase our RailsApps tutorials.

Problems? Issues?
-----------

Need help? Ask on Stack Overflow with the tag 'railsapps.'

Your application contains diagnostics in the README file. Please provide a copy of the README file when reporting any issues.

If the application doesn't work as expected, please [report an issue](https://github.com/RailsApps/rails_apps_composer/issues)
and include the diagnostics.

Ruby on Rails
-------------

This application requires:

- Ruby 2.2.4
- Rails 4.2.0

Learn more about [Installing Rails](http://railsapps.github.io/installing-rails.html).

Getting Started
---------------

Whatever you do, stick as close as possible to the Devise Guide the first time you create your app. You can do MySQL
but will likely have problems with migrations (pending when they have already been run). And some (maybe all?)
of the views will not work if you select any theme except "None" == 1

Hopefully find some solutions for the Guide source code for that issue.

This one uses SQLite. Although I could easily have used MySQL. If migrations cause an issue as above, simply
delete the migrations afterward.

Also if you are using MAMP you'll have to either set the socket location in the database.yml (socket: <path>) or
you can do a symbolic link to the MAMP mysql.sock. Note: finder doesn't show it, you have to go to MAMP tmp via
command line. /Applications/MAMP/tmp/mysql/mysql.sock

Documentation and Support
-------------------------

Issues
-------------

Similar Projects
----------------

Contributing
------------

Credits
-------

License
-------
