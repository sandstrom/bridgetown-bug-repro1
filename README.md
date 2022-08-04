# Bridgetown Bundle Install Bug Reproduction

Steps to reproduce:

- Install direnv (https://direnv.net/docs/installation.html). For macOS it's `brew install direnv`.
- CD into this directory, and run `direnv allow` to active it.
- Run `bundle install`.
- Run `bin/bridgetown start`.
