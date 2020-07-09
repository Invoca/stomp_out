PRIVATE_GEM_SERVER = 'https://gem.fury.io/invoca'
PUBLIC_GEM_SERVER = 'https://rubygems.org'

source PRIVATE_GEM_SERVER
source PUBLIC_GEM_SERVER

gem 'json', '~> 2.3'

gem 'rake', '~> 10.0', :group => [:test, :development]

group :test do
  gem 'flexmock', '~> 1.0'
  gem 'rspec', '~> 2.13.0'
  gem 'right_develop', '~> 3.1'
  gem 'eventmachine', '~> 1.0'
  gem 'faye-websocket', '~> 0.7.5'
  gem 'websocket-driver', '~> 0.3.5'
  gem 'rack', '~> 1.5'
  gem 'websocket-rack', '~> 0.4'
  gem 'thin'
end

group :development do
  gem 'jeweler', '~> 2.0'
  gem 'ruby-debug', :platforms => [:ruby_18]
  gem 'pry', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'pry-byebug', :platforms => [:ruby_20, :ruby_21]
end
