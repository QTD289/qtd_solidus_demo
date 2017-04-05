source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

ruby '2.3.1'
gem 'rails', '~> 5.0.2'
gem 'pg'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'pry-rails'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Rails e-commerce
gem 'solidus', '2.1'
gem 'solidus_auth_devise'

# Improved view for payment logs
gem 'solidus_log_viewer', github: 'solidusio-contrib/solidus_log_viewer'

# Content management of pages for Solidus
gem 'solidus_static_content', github: 'solidusio-contrib/solidus_static_content'

# Adds support for WYSIWYG editors to Solidus
gem 'solidus_editor', github: 'solidusio-contrib/solidus_editor', branch: 'master'

gem 'solidus_wishlist', github: 'boomerdigital/solidus_wishlist', branch: 'master'
