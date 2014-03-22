## code4sac.github.io

http://code4sac.org

### Running Locally

code4sac.org is run on GitHub pages, and uses [Jekyll][jekyll].

##### Pre-requisites

1. [Ruby][ruby]
2. [Bundler][bundler]

Once you have satisfied the pre-requisites, install the Ruby Gem dependencies:

    bundle install

This will install Jekyll which is used to compile the site.

Now fire up Jekyll:

    jekyll serve --watch

This will start up a web server at `http://localhost:4000` that will serve the site content on your computer.

Whenever you make a change, Jekyll will automatically re-compile the site's content and it will instantly be available in your local copy for you to play with.

That's it!

[jekyll]: http://jekyllrb.com/
[ruby]: https://www.ruby-lang.org/en/downloads/
[bundler]: http://bundler.io