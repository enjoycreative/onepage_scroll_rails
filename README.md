# OnepageScrollRails

Adding [onepage-scroll](https://github.com/peachananr/onepage-scroll) in rails assets.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'onepage_scroll_rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install onepage_scroll_rails

## Usage

Add in application.css

```sass
@import 'onepage-scroll/onepage-scroll'
```

Add in application.js

```coffee
#= require 'onepage-scroll/jquery.onepage-scroll'
```
or
```coffee
#= require 'onepage-scroll/jquery.onepage-scroll.min'
```

Use it like [here](https://github.com/peachananr/onepage-scroll). Docs and more info is placed [here](https://github.com/peachananr/onepage-scroll) too.


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/red-rocks/onepage_scroll_rails.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
