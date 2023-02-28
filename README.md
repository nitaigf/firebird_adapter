# FirebirdAdapter

ActiveRecord Firebird Adapter for Rails 6 and 7.

According to our new versioning strategy use:
- firebird_adapter 7.x for Rails 7.x (this experimental gem - https://github.com/nitaigf/firebird_adapter)
- firebird_adapter 6.x for Rails from 6.x (from original gem - https://github.com/FabioMR/firebird_adapter)

## Installation

Add in your Gemfile:

```ruby
gem 'firebird_adapter', '7.0', , git: 'https://github.com/nitaigf/firebird_adapter'
```


And then execute:

    $ bundle

## Usage

Configure your database.yml:

```ruby
development:
  adapter: firebird
  host: localhost
  database: db/development.fdb
  username: SYSDBA
  password: masterkey
  encoding: UTF-8
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
