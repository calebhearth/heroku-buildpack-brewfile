Heroku Buildpack Brewfile
=========================

Install packages with [Homebrew](https://github.com/Homebrew/brew)'s Brewfile.

Usage
-----

Add your dependencies to Brewfile and run `brew bundle` to install and lock dependencies. Be sure to commit Brewfile.lock.json, as that's what is used to detect that this buildpack should be used.


License
----
MIT
