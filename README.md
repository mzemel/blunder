# Blunder

Welcome to Blunder, the worst way to manage your Ruby application's dependencies.  Blunder provides an inconsistent environment for Ruby projects by randomly uninstalling the exact gems and versions that are needed.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'blunder', git: "git@github.com:mzemel/blunder.git"
```

And then execute:

    $ bundle install --binstubs

## Usage

Use Blunder with

    $ bin/blunder install

Or try another command!

    $ bin/blunder clean

![](http://i.imgur.com/79Lp33i.png)

