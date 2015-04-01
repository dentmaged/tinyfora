= tinyfora

Thanks to craigp for making tinyfora! I have only cleaned it up and fixed bugs.

== Installation

```
git clone git@github.com:dentmaged/tinyfora.git
cd tinyfora
bundle install
```

== Running

Tinyfora uses Sinatra by default, but for production I recommend Thin.

=== Sinatra
```
ruby app.rb
```

If you get a bug to do with tilt, sinatra and sinatra-contrib run the following command to start the server:
```
bundle exec ruby app.rb
```

=== Thin
```
thin start
```
