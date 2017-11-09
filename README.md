# website

Public facing website for Tandem

## Installation

1.  Install RVM via `\curl -sSL https://get.rvm.io | bash -s stable`
1.  Install Ruby 2.3.0 via `rvm install ruby-2.3.0`
1.  Create a gemset called 'tandem'
    1.  by `rvm gemset create tandem`
    1.  then use gemset via `rvm gemset use tandem`
1.  Install bundler to 'tandem' via `gem install bundler`
1.  Install gems via `bundle install`

## Development

Run in local dev mode via:

1. `rvm use ruby-2.3.0`
1. `rvm gemset use tandem`
1. `jekyll serve`
