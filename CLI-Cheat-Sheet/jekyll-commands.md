Jekyll Commands
====

Jekyll is a simple, blog-aware, static site generator.

### Resources

* [Jekyll official site](https://jekyllrb.com/)
* [Build A Blog With Jekyll And GitHub Pages](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)


Requirements
----

Install [Ruby](https://www.ruby-lang.org/en/downloads/) on your machine.


Installing Jekyll
----

`$ gem install jekyll`


Quickstart:
----

```bash
$ jekyll new my-site
$ cd my-site
$ jekyll build
$ jekyll serve    # => Browse your site @ http://localhost:4000
```


[Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
----

Install [Bundler](http://bundler.io/):

`$ gem install bundler`

Specify your dependencies in a Gemfile in your project's root:

```ruby
source 'https://rubygems.org'

gem 'github-pages'
```

Install all of the required gems from your specified sources:

`$ bundle install`


Jekyll basic usage with Bundler
----

Build site using default `_config.yml` file:

`$ bundle exec jekyll build` - Build site will be generated into `./_site`

`$ bundle exec jekyll build --watch` - Build site into `./_site` and for watch changes

`$ bundle exec jekyll serve` - Serve site at `http://localhost:4000`

Override config (`_config_dev.yml`) for local development test:

`$ bundle exec jekyll build --config _config.yml,_config_dev.yml` - Build site

`$ bundle exec jekyll build --config _config.yml,_config_dev.yml --watch` - Build site and watch changes

`$ bundle exec jekyll serve --config _config.yml,_config_dev.yml` - Serve site at `http://localhost:4000`
