# -*- mode: ruby -*-

require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:test) do |t|
  t.rspec_opts = [ '--format documentation', '--color' ]
end

task :default => :test

