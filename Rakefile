# frozen_string_literal: true

require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
  t.pattern = 'spec/unit/**/*_spec.rb'
end

RSpec::Core::RakeTask.new(:acceptance) do |t|
  t.pattern = 'spec/acceptance/**/*_spec.rb'
end

task default: [:spec, :acceptance]
