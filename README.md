# RuboCop::Git

RuboCop for git diff. 

Forked from https://github.com/radamanthus/rubocop-git and applied fixes:
- https://github.com/m4i/rubocop-git/issues/38

## Installation

Add this line to your application's Gemfile:

    gem 'rubocop-git', git: 'https://github.com/vovanmozg/rubocop-git' 

And then execute:

    $ bundle

## Usage

    Usage: rubocop-git [options] [[commit] commit]
        -c, --config FILE                Specify configuration file
        -r, --require FILE               Require Ruby file
        -d, --debug                      Display debug info
        -D, --display-cop-names          Display cop names in offense messages
            --cached                     git diff --cached
            --staged                     synonym of --cached
            --hound                      Hound compatibility mode

## Contributing

1. Fork it ( https://github.com/vovanmozg/rubocop-git/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
