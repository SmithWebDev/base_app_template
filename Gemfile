source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.0.7", ">= 7.0.7.2"
gem "propshaft"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "cssbundling-rails"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Project Gems
gem 'annotate', '~> 3.2', group: :development
gem 'better_errors', '~> 2.10', group: :development
gem 'binding_of_caller', '~> 1.0', group: :development
gem 'ffaker', '~> 2.21', groups: %i[development test]
gem 'hirb', '~> 0.7.3'
gem 'hotwire-livereload', '~> 1.2'
gem 'model_probe', '~> 1.1'
gem 'view_components', '~> 0.1.0'
gem 'friendly_id', '~> 5.4.0'

group :development, :test do
  gem 'ruby-lsp', require: false
  gem "ruby-lsp-rails"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

