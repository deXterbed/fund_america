# FundAmerica

This is a ruby gem to provide easy implementation of FundAmerica API

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'fund_america'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fund_america

## Usage

The details on usage of FundAmerica gem are present at: http://www.rubyeffect.com/blog/category/fundamerica/. If you wish to see FundAmerica's API documentation, please visit the url: https://apps.fundamerica.com/support/documentation

1. FundAmerica Gem Introductory Post - http://www.rubyeffect.com/blog/fundamerica-gem/
2. Entity Endpoints Part One - http://www.rubyeffect.com/blog/fundamerica-gem-entity-endpoints/
3. Entity Endpoints Part Two - http://www.rubyeffect.com/blog/fundamerica-gem-entity-endpoints-part-two/

## TODO

1. Addition of new end points as per the latest FundAmerica latest changelog
2. Addition of paginated results fetch, sorting and hide options for resource_list responses
3. Support for ruby versions < 2.2.2
4. More test cases

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/rubyeffect/fund_america/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
