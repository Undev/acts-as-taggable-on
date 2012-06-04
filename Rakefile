require 'rubygems'
require 'bundler'

require 'spec/version'
require 'spec/rake/spectask'
require 'spec/ruby'

Bundler.setup :default, :development

desc 'Default: run specs'
task :default => :spec  

desc "Run all specs"
Spec::Rake::SpecTask.new(:spec) do |t|
  t.spec_files = FileList['spec/**/*_spec.rb']
end

Bundler::GemHelper.install_tasks
