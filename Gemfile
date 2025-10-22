source "https://rubygems.org"

gem "arclight"
gem "blacklight-locale_picker"
gem "bootsnap", require: false
gem "bootstrap", "~> 5.3"
gem "change_the_subject"
gem "cssbundling-rails"
gem "devise"
gem "devise-guests", "~> 0.8"
gem "importmap-rails"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "propshaft"
gem "puma", ">= 5.0"
gem "rails", "~> 8.1.0"
gem "rsolr", ">= 1.0", "< 3"
gem "stimulus-rails"
gem "thruster", require: false
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Use the database-backed adapters for Rails.cache, Active Job, and Action Cable
gem "solid_cable"
gem "solid_cache"
gem "solid_queue"


# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "brakeman", require: false
  gem "database_cleaner"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "factory_bot_rails"
  gem "rails-controller-testing"
  gem "rspec-rails"
  gem "rubocop-rails-omakase"
end

group :development do
  gem "foreman"
  gem "listen"
  gem "web-console"
end

group :test do
  gem "capybara", ">= 3.18"
  gem "rspec_junit_formatter"
  gem "simplecov", require: false
  gem "timecop"
  gem "webdrivers"
  gem "webmock"
end
