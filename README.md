## Ruby Project to learn Ruby

This project is my learning ruby by following a tutorial

**The following steps will create the same environment on your local machine and you will be able to clone this project so that it will work on your Mac.**

#### Install Command line tools on terminal

```sh
$ xcode-select --install
```

#### Install Homebrew
```sh
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Install rbenv
```sh
$ brew update
$ brew install rbenv ruby-build
$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
$ echo 'export PATH="$HOME/.rbenv/shims:$PATH"' >> ~/.bash_profile
$ source ~/.bash_profile
```

#### Install Ruby
```sh
$ rbenv install 2.2.1
$ rbenv global 2.2.1
$ ruby -v
```

#### Install Rails
```sh
$ gem install rails -v 4.2.0 --no-ri --no-rdoc
$ rbenv rehash
```

#### check your versions
```sh
$ ruby -v
# ruby 2.2.1

$ rails -v
# Rails 4.2.0
```

#### Also need to install bootstrap
```sh
$ bundle install
```

#### U can now runserver by typing the following in your projects root directory
```sh
rails s
```

[Click Here to launch your local server](http://localhost:3000/)
