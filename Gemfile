source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'sinatra'
gem 'haml'

group :test do
  gem 'rake'
  gem 'test-unit'
  gem 'rack-test'
  #gem 'minitest'
  gem 'mocha'
  #gem 'timecop'
end
