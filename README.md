
Redcase
=======

Test case management plug-in for Redmine
----------------------------------------

Redcase allows you to create, manage, and execute test cases, group them into
test suites, link them with the native Redmine issues, work with multiple test
environments, create reports, and more.

Please see the project's [Wiki](https://bitbucket.org/bugzinga/redcase/wiki) for
more information.

## Redcase

- Redcase is a Test Case management plugin developed for Redmine project managment web framwork written using Ruby on Rails.
- This plugin wad developed by Bugzinga Team for Redmine, which is compatible with Redmine 3.1.x, 3.1.0
- On 9 Apr 2020 the Bugzinga Team updated this plugin which is compatible with redmine 4.0.x
- Now redmine 5.0.1 is released and in this version of redmine the Zeitwerk autoloader is added, from the very begining and upto Rails 5 autoloader is implemented in active support. From Rails 7 the autoloader does not include any more.
- Starting with Rails 6, Rails ships new and better way to autoload, which is Zeitwerk gem.
- The advantage of this Zeitwerk gem is, we don't need to mention "require patch" in init.rb file of the plugin.
#### We make this Redcase plugin compatible with Redmine 5.0.1
