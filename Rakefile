require 'rake'

desc "Default task"
task :default do
  puts "Running the default Rake task..."
end

desc "Say hello"
task :say_hello do
  puts "Hello from Rake!"
end

desc "Run the main script"
task :run_main do
  ruby "src/main.rb"
end

desc "Build the application"
task :build do
  puts "Building the application..."
  sh "mkdir -p build && cp src/main.rb build/main.rb"
  puts "Build completed successfully."
end
