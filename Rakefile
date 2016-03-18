$:.unshift File.expand_path('../lib', __FILE__)

task :build do
  system 'mvn install'
  system 'gem build geotools-jars.gemspec'
end

task :release => :build do
  system 'gem push geotools-jars-15.0-java.gem'
end
