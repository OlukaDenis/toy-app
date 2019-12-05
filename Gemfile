source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'


gem 'rails', '6.0.1'
gem 'autoprefixer-rails', '9.6.1.1'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '5.0.0'
gem 'jquery-rails', '4.3.5'
gem 'puma', '4.3.1'
gem 'font-awesome-rails', '4.7.0.5'
gem 'sass-rails', '6'
gem 'webpacker', '4.0'
gem 'turbolinks', '5'
gem 'jbuilder', '2.9.1'
gem 'rubocop', '0.77.0'
gem 'bootsnap', '1.4.2', require: false

group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'web-console', '3.3.0'
  gem 'listen', '3.2.0'
  gem 'spring'
  gem 'spring-watcher-listen', '2.0.0'
end

group :test do
  gem 'capybara',           '3.28.0'
  gem 'selenium-webdriver', '3.142.4'
  gem 'webdrivers',         '4.1.2'
end

group :production do
  gem 'pg',  '0.20.0'
  # gem 'fog', '1.42'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
