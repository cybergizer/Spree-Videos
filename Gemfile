source 'http://rubygems.org'
gemspec

group :test do
  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'guard-rspec'
    gem 'rb-fsevent'
    gem 'growl'
  end
  gem 'coffee-rails'
end

gem 'spree', '~> 3.1'
gem 'spree_auth_devise', :github => 'spree/spree_auth_devise', :branch => '3-1-stable'
gem 'sass-rails'
