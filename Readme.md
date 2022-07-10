# Ballet Website

## Development pre-setup with nix

In the directory run nix-shell.

## Development pre-setup without nix

Install rbenv (see <https://github.com/rbenv/rbenv>) and with that the most recent ruby.

## Setup

Once you have the right version of ruby installed, install bundler: `gem install bundler`

## Reconfiguring

When setting up the first time or after changing the Gemfile run `bundler install` to make sure that all the right dependencies are in place.

## Running

To run the webserver simply `bundle exec jekyll serve`.
