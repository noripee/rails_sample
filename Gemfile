ruby '2.2.3'

source 'https://rubygems.org' do
  gem 'coffee-rails'
  gem 'jbuilder'
  gem 'jquery-rails'                 # [option] JQuery使うなら
  gem 'mysql2'
  gem 'rails', '4.2.4'
  gem 'sass-rails'
  gem 'slim-rails'
  gem 'uglifier'
  gem 'virtus'                       # [option] ActiveRecord以外のModelやattributesを作るならオススメ

  group :doc do
    gem 'yard'
  end

  group :development, :test do
    gem 'better_errors'
    gem 'bullet'
    gem 'capybara'                   # [option] E2Eテストするならcapybara推奨
    gem 'capybara-screenshot'
    # [option] capybara使うならオススメ
    gem 'factory_girl_rails'
    gem 'ffaker'
    gem 'json_expressions' # [option] JSON APIがあるならオススメ
    gem 'launchy'
    # [option] capybara使うならオススメ
    gem 'poltergeist' # [option] E2EテストでJS動かすなら推奨
    gem 'pry-byebug'
    gem 'pry-rails'
    gem 'rubocop', require: false
    gem 'web-console', '~> 2.0'
  end

  group :test do
    gem 'database_rewinder'
    gem 'rspec-rails'
    gem 'rspec_junit_formatter'
    gem 'simplecov', require: false
  end

  group :production do
    gem 'dotenv-rails'
    gem 'unicorn', '~> 4.9.0'
  end
end
