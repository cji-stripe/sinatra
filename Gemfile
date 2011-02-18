# Why use bundler?
# Well, not all development dependencies install on all rubies. Moreover, `gem 
# install sinatra --development` doesn't work, as it will also try to install
# development dependencies of our dependencies, and those are not conflict free.
# So, here we are, `bundle install`.
#
# If you have issues with on gem: `bundle install --without-coffee-script`.

source :rubygems
gemspec

gem 'rake'
gem 'rack-test', '>= 0.5.6'

gem 'haml', '>= 3.0', :group => 'haml'
gem 'builder', :group => 'builder'
gem 'erubis', :group => 'erubis'
gem 'less', :group => 'less'
gem 'liquid', :group => 'liquid'
gem 'RedCloth', :group => 'redcloth'
gem 'rdoc', :group => 'rdoc'
gem 'nokogiri', :group => 'nokogiri'
gem 'slim', :group => 'slim'

gem 'coffee-script', '>= 2.0', :group => 'coffee-script'

platforms :ruby do
  gem 'rdiscount', :group => 'rdiscount'
end

platforms :ruby_18, :jruby do
  gem 'json', :group => 'coffee-script'
  gem 'markaby', :group => 'markaby'
  gem 'radius', :group => 'radius'
end