source "http://rubygems.org"

gemspec

gem 'rails'

platform :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'racc'
end

group :test, :development do
  gem 'byebug', platform: :mri_21, require: false
end

group :development do
  gem 'puma'
end

group :test do
  gem 'codeclimate-test-reporter', require: nil
end
