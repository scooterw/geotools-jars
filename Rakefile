$:.unshift File.expand_path('../lib', __FILE__)

task :build do
  system 'gem build geotools-jars.gemspec'
end

task :release => :build do
  system 'gem push geotools-jars-9.3-java.gem'
end

