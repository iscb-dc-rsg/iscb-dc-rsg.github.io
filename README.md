# ISCB DC-RSG Web Page

The ISCB DC-RSG homepage makes use of the [Skinny Bones](https://mmistakes.github.io/skinny-bones-jekyll/getting-started/) Jekyll theme.

In order to make changes to the website, you will first need to install the
[Jekyll](https://jekyllrb.com/) and [Bundler](http://bundler.io/) ruby packages
using the `gem` command, and then use the `bundle` command to install the
theme-specific settings:

    gem install --user jekyll bundler

Next, clone this repo and `cd` into th root directory and run:

    bundle install --path vendor/bundle

Now you should be all set! Whenever you want to make changes to the site, e.g.
to `_config.yml` or `_data/navigation.yml`, simply run the command `bundle exec
jekyll build` to re-render the markdown into HTML, verify that the changes look
good, and commit and push them back upstream




