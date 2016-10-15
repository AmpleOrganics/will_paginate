source 'http://rubygems.org'

rails_version = '~> 2.3.6'

gem 'actionpack',   rails_version
gem 'activerecord', rails_version

gem 'rake', '~> 0.8.7'
gem 'mocha', '0.9.7'
gem 'sqlite3', '~> 1.3.6'
gem 'mysql', '~> 2.9', :group => :mysql

group :pg do
  gem 'postgres', :platforms => :ruby_18
  gem 'pg', '~> 0.17.0', :platforms => :ruby_19
end

group :development do
  gem 'ruby-debug', :platforms => :mri_18
  gem 'debugger', :platforms => [:mri_19, :mri_20]
end
