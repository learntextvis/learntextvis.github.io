# learntextvis.github.io

The Learn Text Vis Website


## Installation

To work on the site locally, you will need a few things.

First, we need to clone the site locally and navigate to its directory:

```
git clone git@github.com:learntextvis/learntextvis.github.io.git

cd learntextvis.github.io
```

This site is powered by [Jekyll](https://jekyllrb.com/), a popular ruby static site generator.

The ruby gem dependencies are managed by [Bundler](http://bundler.io/).

First, ensure `bundler` is installed:

```
gem install bundler
```

Now we can use the `bundle` command to install all the packages required for this site.

```
bundle install
```

This command will read the local `Gemfile` and download the required ruby gems.

## Running Locally

Assuming everything installs without issue, you should be able to start a local server to serve this site using:

```
make watch
```

Behind the scenes, this is really just running `jekyll`. It is equivalent to this command:

```
bundle exec jekyll serve
```

The Make command just makes it easier to remember.

## Modifying Content

Almost all the content for the site is in the `_posts` directory.

### Chapter Naming

Each "chapter" is its own markdown file. The naming convention follows the following convention:

```
YEAR-MONTH-DAY-cXX-NAME.md
```

The date in the name is a requirement of Jekyll - as it is traditionally used for blog posts. Here, we have used the same date for each chapter - so that the order is based on the `cXX` component of the name.

The `NAME` section is optional and provides some details on the contents of the chapter.

### Chapter Content
