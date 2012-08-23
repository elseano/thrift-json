# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "thrift-json"
  gem.homepage = "http://github.com/elseano/thrift-rb-json"
  gem.license = "Apache License, Version 2.0"
  gem.summary = %Q{The missing JsonProtocol from Thrift}
  gem.description = %Q{The missing JsonProtocol from Thrift}
  gem.authors = ["Apache Thrift"]
  gem.files = ["lib/**/*.rb"]
  # dependencies defined in Gemfile
end

Jeweler::RubygemsDotOrgTasks.new
