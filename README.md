# Rspec::Engine::Generator

Simple Thor based gem that lets you easily create a Rails 3 engine.
Standard Rails prefers TestUnit and it's not obvious or trivial to set
things up yourself, so I've bundled together great ideas from
http://brainbicycle.net/blog/2011/10/03/create-a-rails-engine-with-rspec-and-capybara-tests
and elsewhere and tried to make this simple and easy.

## Installation

  $ gem install rspec_engine_generator

## Usage

Usage:
  rspec\_engine new NAME

Options:
  [--mountable]  # choose whether to make the engine mountable or not
(if false, engine is --full)
                 # Default: true

Build a new rspec-ready engine named NAME

## Notes

Looks like there's some wonkiness going on if you generate an engine
with a dash in it. So, name your engines foo\_engine not foo-engine to
avoid a headache.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
