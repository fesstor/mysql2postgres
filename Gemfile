ruby '1.9.3'
source 'https://rubygems.org'

gem 'rake', '~> 10.3'
gem 'mysql-pr', '~> 2.9'
gem 'postgres-pr', '0.6.3'

platforms :jruby do
  gem 'activerecord'
  gem 'jdbc-postgres'
  gem 'activerecord-jdbc-adapter'
  gem 'activerecord-jdbcpostgresql-adapter'
end

platforms :mri_19 do
  gem 'pg', '~> 0.17'
end

gem 'test-unit'

group :test do
  gem 'jeweler', '~> 2.0'
end

# gem 'mysqltopostgres', '0.2.20', :path => './'
