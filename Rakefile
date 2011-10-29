require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "ffi-libfreenect"
    gem.summary = gem.description = %Q{FFI bindings for the libfreenect OpenKinect library}
    gem.homepage = "http://github.com/jgrunzweig/ffi-libfreenect"
    gem.authors = ["Josh Grunzweig", "Eric Monti"]

    gem.rdoc_options += ["--title", "FFI Freenect", "--main",  "README.rdoc", "--line-numbers"]
    gem.add_dependency("ffi", ">= 0.5.0")

    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

#require 'spec/rake/spectask'
#Spec::Rake::SpecTask.new(:spec) do |spec|
#  spec.libs << 'lib' << 'spec'
#  spec.spec_files = FileList['spec/**/*_spec.rb']
#end

#Spec::Rake::SpecTask.new(:rcov) do |spec|
#  spec.libs << 'lib' << 'spec'
#  spec.pattern = 'spec/**/*_spec.rb'
#  spec.rcov = true
#end

#task :spec => :check_dependencies

#task :default => :spec

begin
  require 'yard'
  YARD::Rake::YardocTask.new
rescue LoadError
  task :yardoc do
    abort "YARD is not available. In order to run yardoc, you must: sudo gem install yard"
  end
end
