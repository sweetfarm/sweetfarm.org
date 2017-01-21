## Project Setup

### Installing Ruby

If this is your first time running the project, you'll need to make sure you have the correct 
version of Ruby installed locally. We use homebrew to do this and, if you don't have it
installed locally, you can do so using the following command:

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Once homebrew is installed, you can use it to install the correct Ruby. Do that using the
following command:

```sh
brew install ruby
```

## Installing Bundler

Bundler is a Ruby program that is used to manage the tooling dependencies for this project.
We'll need it in order to continue. If you don't already have bundler installed, you can
install it using the following command:

```sh
gem install bundler
```

### Installing Octopress

This project is a Jekyll blog that runs on Github's CDN. As such, we can use the `octopress`
tool to manage the project's content, deployment and administration. We can use bundler
to install this dependency, along with every other tool we'll need:

```sh
bundle install
```

## Running The Blog

To run the blog locally, simply use the `jekyll` command

```sh
bundle exec jekyll serve
```
