# POC.github.io

POC de github page official for Tecnocratas digitales

## Setting up ruby

Install, on Ubuntu:

``` bash
sudo apt install ruby-full
```

Add to ~/.bashrc

``` bash
export GEM_HOME=$HOME/.gem
export GEM_PATH=$HOME/.gem
```

For working with ruby it is encouraged to use [rbenv](https://github.com/rbenv/rbenv)
and [Bundler](https://bundler.io/) for painless Ruby upgrades and environment.


``` bash
# install with curl
curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-installer | bash
# Install rbenv for managing enabling of multiple rubies.
git clone git://github.com/sstephenson/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
exec $SHELL
rbenv install 2.7.1
rbenv local 2.7.1
```

More details at:
https://www.ruby-lang.org/en/downloads/
https://github.com/rbenv/rbenv

## Done steps

Not necessary anymore

``` bash
bundle exec jekyll new --force --skip-bundle .
bundle install
```
