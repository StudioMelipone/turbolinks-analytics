Turbolinks::Analytics
=====================

Drop-in Analytics support for your Rails applications running with [Turbolinks](https://github.com/rails/turbolinks). Add your analytics scripts in your application layout like you would normally do. Make sure your analytics tool is [supported](#supported-services).


Installation
------------

1. Follow [Turbolinks installation guide](https://github.com/rails/turbolinks#installation).
1. Add `gem turbolinks-analytics` to your Gemfile.
1. Run `bundle install`.
1. Add `//= require turbolinks-analytics` to your Javascript manifest file.
1. Restart your server.


Supported Services
------------------

- [Google Analytics](http://www.google.com/analytics/)
- [Gauges](http://get.gaug.es)
