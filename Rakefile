begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = %q{default_value_for}
    gem.version = "0.1.0"
    gem.summary = %q{Provides a way to specify default values for ActiveRecord models}
    gem.description = %q{The default_value_for plugin allows one to define default values for ActiveRecord models in a declarative manner}
    gem.email = %q{info@phusion.nl}
    gem.homepage = %q{http://github.com/FooBarWidget/default_value_for}
    gem.authors = ["Hongli Lai"]
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :default => :test

desc "Run unit tests."
task :test do
	ruby "test.rb"
end
