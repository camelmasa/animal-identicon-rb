# Animal::Identicon

Ruby library for generation animal icons using SVG.
It's like identicon but only 4096 patterns. (64 animals and 64 colors)

![](https://user-images.githubusercontent.com/189824/38244739-93b970e6-3776-11e8-8e8f-608faf59ac8b.png)


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'animal-identicon'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install animal-identicon

## Usage

```
require "animal-identicon"

icon = Animal::Identicon.new("camelmasa")
icon.to_svg(64)
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/'camlemasa'/animal-identicon-rb.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
