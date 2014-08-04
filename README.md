# scrivito : CRM Event Widget

[![Gem Version](https://badge.fury.io/rb/scrivito_crm_event.svg)](http://badge.fury.io/rb/scrivito_crm_event)
[![Code Climate](https://codeclimate.com/github/gertimon/scrivito_crm_event.png)](https://codeclimate.com/github/gertimon/scrivito_crm_event)

A Widget for Scrivito and Infopark CRM.

## Installation

Add this line to your application's `Gemfile`:

    gem 'scrivito_crm_event'

Add this line to your application Stylesheet manifest:

    *= require scrivito_crm_event/application

You also need a working connection to your Infopark CRM.

And then execute:

    $ bundle
    $ rake cms:migrate:install
    $ rake cms:migrate
    $ rake cms:migrate:publish

## Changelog

See [Changelog](https://github.com/gertimon/scrivito_crm_event/blob/master/CHANGELOG.md) for more
details.

## Contributing

1. Fork it ( https://github.com/infopark/scrivito_crm_event/merge_tags/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request