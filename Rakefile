require 'bundler'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'test'
  t.pattern = "*_test.rb"
end

desc 'Run tests'
task default: :test
