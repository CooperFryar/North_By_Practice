source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.4"

gem "rails", "~> 7.1.3"
gem "propshaft", ">= 0.7.0"
gem "pg", "~> 1.1"
gem "puma", "~> 6.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "cssbundling-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "bootsnap", require: false

# New gems added from the new list
gem "activerecord-postgres_enum"
gem "awesome_print"
gem "date_by_example"
gem "devise"
gem "kredis"
gem "redis", "~> 4.0"
gem "simple_form"
gem "simple_form-tailwind"
gem "table_print"

group :development, :test do
  gem "cypress-rails"
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails"
  gem "faker"
  gem "pry-rails"
  gem "pry-rescue"
  gem "rspec-rails"
  gem "standard"
  gem "test-prof"
end

group :development do
  gem "annotate"
  gem "erb_lint", require: false
  gem "htmlbeautifier"
  gem "listen"
  gem "rack-mini-profiler"
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "capybara-screenshot"
  gem "factory_bot_rails"
  gem "selenium-webdriver"
end
