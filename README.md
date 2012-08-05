# Activerecord-Mysql2-Adapter

This is an extract from the original and awesome mysql2 repository. If you
do not need the latest and greatest of the mysql2-gem, you can and maybe
should stick to mysql2, version ~> 0.2.18

## Installation

### Using Bundler

Add this line to your application's Gemfile:

    gem 'activerecord-mysql2-adapter'

And then execute:

    $ bundle

### old-style Rails

Rails without Gemfile shoudld either be ported to be using Bundler (you can
thank me later) or you can do what you probably would do anyway: Add the
following line to the appropriate environment-file(s).

    config.gem 'activerecord-mysql2-adapter'

### DIY

Or install it yourself as:

    $ gem install activerecord-mysql2-adapter

## Usage

It's giving you a connection between the gems activerecord and mysql2. You
are using this one most likely implicitly.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Credits

Most of the credit goes to the contributors and maintainers of mysql2.
I just copied the files. So, If you need professional Copy-Paste-work,
contact me. :)

The original work is under the MIT-LICENSE and so is this.
