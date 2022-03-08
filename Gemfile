source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails',      '6.1.4.1'
gem 'puma',       '5.3.1'
gem 'sass-rails', '6.0.0'
gem 'webpacker',  '5.4.0'
gem 'turbolinks', '5.2.1'
gem 'jbuilder',   '2.10.0'
#gem 'bootsnap',   '1.7.2', require: false
gem 'bulma-rails', '~> 0.9.3'
gem 'simple_form', '~> 5.1'
gem 'gravatar_image_tag', '~> 1.2'
gem 'devise', '~> 4.8', '>= 4.8.1'
group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug',  '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',        '4.1.0'
  gem 'rack-mini-profiler', '2.3.1'
  gem 'listen',             '3.4.1'
  gem 'spring',             '2.1.1'
  gem 'better_errors', '~> 2.9', '>= 2.9.1'
  gem 'guard', '~> 2.18'
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2',require: false
end

group :test do
  gem 'capybara',           '3.35.3'
  gem 'selenium-webdriver', '3.142.7'
  gem 'webdrivers',         '4.6.0'
end

group :production do
  gem 'pg', '1.2.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
gem 'tzinfo-data' #, platforms: [:mingw, :mswin, :x64_mingw, :jruby]