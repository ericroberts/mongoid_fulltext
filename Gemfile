source "http://rubygems.org"

if ENV['TRAVIS']
  gem "mongoid", "~> #{ENV['MONGOID']}"
else
  gem "mongoid", "~> 4.0.0.beta1"
end

gem "unicode_utils", "~> 1.0.0"

group :development, :test do
  gem "bundler"
  gem "rspec", "~> 2.10.0"
  gem "jeweler", "~> 2"
end
