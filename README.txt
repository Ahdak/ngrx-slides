# Prérequis 
- ruby, gem, bundler installed

# New presentations
- touch Gemfile
- copy and paste to Gemfile

source 'https://rubygems.org'

gem 'asciidoctor-revealjs' # latest released version

- bundle config --local github.https true
- bundle --path=.bundle/gems --binstubs=.bundle/.bin
- bundle exec asciidoctor-revealjs -a revealjsdir=reveal.js-3.6.0 redux.adoc