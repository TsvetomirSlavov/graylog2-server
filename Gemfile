source :rubygems

gem 'rack', '~> 1.2.2'
gem 'rails', '~> 3.0.6'
gem 'json', '~> 1.5.1'
gem 'jnunemaker-validatable', '1.8.4'
gem 'plucky', '~> 0.3.7'
gem 'mongoid', '~> 2.0.1'
gem 'bson_ext', "~> 1.3.0"
gem 'chronic', '~> 0.3.0'
gem 'pony', '~> 1.1'  # yes, unusual version number
gem 'declarative_authorization', :git => "http://github.com/cipherpunk/declarative_authorization.git"

# TODO move to another group
gem 'eventmachine', '~> 0.12.10'
gem 'em-websocket', '~> 0.1.4'  # TODO upgrade to 0.2.x
if RUBY_VERSION.start_with?('1.8')
  gem 'SystemTimer', '~> 1.2.3'
end

group :development, :test do
  gem 'machinist_mongo', '~> 1.2.0', :require => 'machinist/mongoid'
  gem 'ci_reporter', '~> 1.6.4'
  gem 'shoulda', '~> 2.11.3'
  gem 'mocha', '~> 0.9.12'
  gem 'database_cleaner', '~> 0.6.6'
  gem 'faker', '~> 0.9.5'
  # TODO add, configure and actually use metric_fu
end
