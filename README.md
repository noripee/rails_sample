# homebrew
```bash
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# rbenv
```bash
$ brew update
$ brew intall readline rbenv ruby-build
$ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
```

```bash
$ rbenv install -l
$ rbenv install 2.2.3
$ rbenv global 2.2.3
$ rbenv rehash
$ ruby -v
```

# bundler
```bash
$ gem install bundler
$ bundle -v
```

# mysql
```bash
$ brew install mysql
```

# direnv
```bash
$ echo 'eval "$(direnv hook bash)"' >> ~/.bashrc
$ echo 'export EDITOR=vi' >> ~/.bashrc
$ source ~/.bashrc
```

# create project directory
```bash
$ mkdir -p project
$ cd project
```

# rbenv
```bash
$ rbenv local 2.2.3
```

# rails
```bash
vi Gemfile
```
```ruby
# Gemfile
source 'https://rubygems.org'
ruby '2.2.3'
gem 'rails', '4.2.4'
```
```bash
$ bundle
$ bundle exec rails new . -TB -d mysql
```

# direnv
```bash
$ direnv edit .
```
```bash
# .envrc
export PATH=$PWD/bin:$PATH
```

# binstub
```bash
$ bundle binstub rspec-core rubocop yard
```

# application.rb
```ruby
config.generators do |g|
  g.template_engine = :slim
  g.helper_specs = false
  g.view_specs = false
  g.factory_girl dif: 'spec/factories'
end
config.time_zone = 'Tokyo'
config.active_record.default_timezone = :local
config.i18n.default_locale = :ja
```

# RSpec
```bash
$ rails g rspec:install
```

# rails_helper.rb
```ruby
Dir[Rails.root.join('spec/supports/*.rb')].each { |f| require f }
```

# rubocop
```bash
$ rubocop
```

# initial commit
```bash
$ git init
$ git add .
$ git ls-files -o
$ git ci -m 'initial commit'
```
