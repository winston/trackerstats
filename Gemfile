source 'http://rubygems.org'

gem 'rails'           , '3.1.3'
gem 'pg'              , '>= 0.11.0'
gem 'haml'            , '>= 3.1.4'
gem 'jquery-rails'    , '>= 1.0.19'

gem 'pivotal-tracker' , git: "git://github.com/jsmestad/pivotal-tracker.git", ref: "ce97c2ae5bb9c6f810d920558e968e1fcc411242"
gem 'google_visualr'  , '>= 2.1.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'    , '>= 3.1.5'
  gem 'coffee-rails'  , '>= 3.1.1'
  gem 'uglifier'      , '>= 1.1.0'
end

group :development do
  gem 'heroku'         , '>= 2.9.0'
  gem 'pivotal_git_scripts'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :test, :development do
  gem 'rspec-rails', '>= 2.7.0'
  gem 'evergreen', require: 'evergreen/rails'
  gem 'ruby-debug19'
  gem 'factory_girl_rails'
end
