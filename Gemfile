source 'http://rubygems.org'

gemspec

gem 'sqlite3'

group :development do
  gem 'jeweler'
end

group :test do
  gem 'rails', '3.1.0.beta', :git => 'git://github.com/bborn/rails.git'
  gem 'rack', :git => 'git://github.com/rack/rack.git'
  gem 'arel',  :git => 'git://github.com/rails/arel.git'
#  gem "meta_search", :git => 'git://github.com/bborn/meta_search.git', :branch => 'rails3.1'
  gem "meta_search", :path => '../meta_search'
  gem 'authlogic', :git => 'git://github.com/bborn/authlogic.git'
  gem 'calendar_date_select', :git => 'http://github.com/paneq/calendar_date_select.git', :branch => 'rails3test'
  gem 'omniauth', :git => 'https://github.com/intridea/omniauth.git'  

  gem 'simplecov'
end
