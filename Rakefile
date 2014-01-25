$:.unshift File.expand_path('../lib', __FILE__)

task :build do
  system 'gem build geotools-jars.gemspec'
end

task :release => :build do
  system 'gem push geotools-jars-8.6-java.gem'
end

