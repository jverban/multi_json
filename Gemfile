source :rubygems

gem 'rake', '>= 0.9'
gem 'yard', '>= 0.8'

platforms :ruby_18 do
  gem 'json', '~> 1.4', :require => nil
end

gem 'json_pure', '~> 1.4', :require => nil

platforms :ruby, :mswin, :mingw do
  gem 'oj', '~> 2.0', :require => nil
  gem 'yajl-ruby', '~> 1.0', :require => nil
end

group :development do
  gem 'kramdown', '>= 0.14'
  gem 'pry'
  gem 'pry-debugger', :platforms => :mri_19
end

group :test do
  gem 'rspec', '>= 2.11'
  gem 'simplecov', '>= 0.4'
end

gemspec
