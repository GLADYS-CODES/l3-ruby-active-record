require_relative './config/environment'
require 'sinatra/activerecord/rake'

# CREATE TASK WITHOUT DESCRIPTION
task :hello_world do
    puts "Hello World"
end
# CREATE TASK WITH DESCRIPTION
desc 'Find .01% of 14M'
task :complex math do
    output = (0.01/100) * 1400000
    puts output
end
# ORGANIZE TASKS IN NAMESPACES