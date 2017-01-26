source "https://rubygems.org"
gemspec

# test application
gem 'rack-test'
gem 'sinatra'

# mocks
gem 'mocha', :require => false

# debugging
gem 'pry'

# benchmarking
gem 'benchmark_suite'

# resolve load order issue
gem 'rake'

# used for variable timer modes
gem 'eventmachine'
gem 'em-synchrony'

platforms :rbx do
  gem 'rubysl', '~> 2.0', '>= 2.0.13'
  gem 'rubinius-developer_tools'
end
