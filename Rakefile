require 'bundler/gem_tasks'
require 'rubocop/rake_task'
require 'rspec/core'
require 'rspec/core/rake_task'

RuboCop::RakeTask.new
RSpec::Core::RakeTask.new(:spec)
task default: %i(rubocop spec)
