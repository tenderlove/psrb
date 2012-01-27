task :test do
  sh "gs -q -sDEVICE=xes -Itest:lib -dBATCH #{Dir['test/**/*.ps'].join ' '}"
end

task :default => :test
