task :test do
  sh "gs -q -sDEVICE=xes -Itest -dBATCH #{Dir['test/**/*.ps'].join ' '}"
end

task :default => :test
