require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "ra-capistrano-recipes"
    gem.summary = %Q{Darkside's Capistrano recipes}
    gem.description = 'Extend the Capistrano gem with these useful recipes'
    gem.email = "rogerio@depoiseuleio.com"
    gem.homepage = "http://github.com/rogerio-augusto/capistrano-recipes"
    gem.authors = ["Phil Misiowiec", "Leonardo Bighetti", "Rogério Augusto"]
    gem.add_dependency('capistrano', ['>= 2.5.9'])
    gem.add_dependency('capistrano-ext', ['>= 1.2.1'])
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end

require 'rake/rdoctask'
Rake::RDocTask.new do |rdoc|
  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = 'capistrano-recipes'
  rdoc.options << '--line-numbers' << '--inline-source'
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end

