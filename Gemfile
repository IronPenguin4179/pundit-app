source 'https://rubygems.org'

git_source(:github) do |repo_name| repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/") 
  "https://github.com/#{repo_name}.git" 
end

gem 'rails', '~> 5.1.2'

gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'devise'
gem 'auto_html'
gem 'acts_as_votable'
gem 'faker'
gem 'sqlite3' 
gem 'web-console', '~> 2.0'
gem 'pundit'

#design
gem 'font-awesome-rails'
gem 'bourbon'
gem 'neat'
gem 'refills'
gem 'normalize-rails'

gem 'sdoc', group: :doc

gem 'puma', '~> 3.0'

gem 'thor', '0.19.1'

group :development do 
  gem 'listen', '~> 3.0.5' 
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'database_cleaner'
  
  gem 'shoulda-matchers'
end



