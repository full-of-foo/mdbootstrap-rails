# mdbootstrap-rails
`mdbootstrap-rails` is make for Rails Project with Bootstrap v4 and
MDB(Material Design Bootstrap) 

Current MDB Version: MDB Free 4.2.0

Documentation:
http://mdbootstrap.com/


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mdbootstrap-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mdbootstrap-rails

## Usage

Edit your `app/assets/javascripts/application.js` file
```javascript
// app/assets/javascripts/application.js
........
//= require tether
//= require bootstrap
//= require mdb
........

```

Edit your `app/assets/stylesheets/application.css` or `app/assets/stylesheets/application.scss` file
```css
// app/assets/stylesheets/application.css
..........
*= require bootstrap
*= require mdb
..........

// app/assets/stylesheets/application.scss
..........
@import "bootstrap";
@import "mdb";
..........
```

## Change Log

Current Version 0.1.0

This link listing [Change
Log](https://github.com/ggomagundan/mdbootstrap-rails/blob/master/CHANGE_LOG.md)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## License

The gem is available as open source under the terms of the [MIT
License](http://opensource.org/licenses/MIT).

