task :test do
  sh "gs -q -sDEVICE=nullpage -Itest:lib -dBATCH #{Dir['test/**/*.ps'].join ' '}"
end

task :default => :test
