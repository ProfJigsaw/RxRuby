#!/usr/bin/env rake
require "bundler/gem_tasks"
require 'rake/clean'
require 'rake/testtask'

Bundler::GemHelper.install_tasks

task default: :test

Rake::TestTask.new do |task|
  task.test_files = FileList['test/**/test*.rb']
end
