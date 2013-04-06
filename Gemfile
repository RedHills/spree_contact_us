source 'http://rubygems.org'

# for testing different spree versions
gem 'spree','1.3.2' :git => 'git://github.com/RedHills/spree.git'#, :branch => "1-2-stable"#, :ref => "ce5bc8812"

# :require needed for this gem
gem "recaptcha", :require => "recaptcha/rails"

# needed due to a quirk of shoulda/rspec integration
# see https://github.com/thoughtbot/shoulda/issues/203
group :test do
  gem 'shoulda-matchers'
end
group :test, :development do
  gem 'rspec-rails'
end

gemspec
