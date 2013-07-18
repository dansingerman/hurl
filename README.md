Hurl
====

Hurl was created for the Rails Rumble 2009 in 48 hours.
Now Hurl is an open source project for your enjoyment.

<http://hurl.it/>

Note: This fork adds an htaccess username password, and if running on heroku, only allows https. In case you want to do something not 100% public.

To get it working on Heroku I had to do this: http://stackoverflow.com/questions/14856468/https-github-com-twilio-hurl-and-heroku

Installation
------------

Hurl requires Ruby 1.8.6+

First download hurl and cd into the directory:

    git clone git://github.com/twilio/hurl
    cd hurl

Or download [the zip](http://github.com/twilio/hurl/zipball/master).

Next make sure you have [RubyGems](https://rubygems.org/pages/download) installed.

Then install [Bundler](http://gembundler.com/):

    gem install bundler

Now install Hurl's dependencies:

    bundle install


Run Locally
-----------

    bundle exec shotgun config.ru

Now visit <http://localhost:9393>

Run in Heroku
-------------

    heroku create
    git push heroku master
    heroku open

This will open a copy of Hurl running on your own private Heroku instance.


Issues
------

Find a bug? Want a feature? Submit an [issue
here](http://github.com/twilio/hurl/issues). Patches welcome!


Screenshot
----------

[![Hurl](http://img.skitch.com/20091020-xtiqtj4eajuxs43iu5h3be7upj.png)](http://hurl.it)


Original Authors
-------

* [Leah Culver][2]
* [Chris Wanstrath][3]


[1]: http://r09.railsrumble.com/
