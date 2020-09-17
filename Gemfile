source 'https://rubygems.org'

gem 'rails', '5.2.4.4'

ruby '2.1.1'

gem 'pg'
gem 'sass-rails', '~> 5.0.5'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'jquery-rails', '>= 4.0.1'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'fog', '~> 1.22.0'
gem 'pry'

group :production do
  gem 'rails_12factor'
end

# spree extensions
gem 'spree', git: 'https://github.com/spree/spree.git', branch: '2-3-stable'
gem 'spree_gateway', git: 'https://github.com/spree/spree_gateway.git', branch: '2-3-stable'
gem 'spree_auth_devise', git: 'https://github.com/spree/spree_auth_devise.git', branch: '2-3-stable'
gem 'spree_mail_settings', git: 'https://github.com/rodolfospalenza/spree_mail_settings.git'
gem 'spree_mobile_endpoints', git: 'https://github.com/ulices/spree_mobile_endpoints', branch: '2-3-stable'
gem 'spree_food_menu', git: 'https://github.com/ulices/spree_food_menu', branch: '2-3-stable'

group :development, :test do
  gem 'database_cleaner'
  gem 'factory_girl_rails', '>= 4.4.1'
  gem 'ffaker'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'rspec-rails', '>= 2.14.2'
end
