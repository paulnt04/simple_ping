require 'rubygems'  
require 'rake'  
require 'echoe'  
  
Echoe.new('simple_ping', '0.1alpha') do |p|  
  p.description     = "Pings a system and returns a boolean"  
  p.url             = "http://github.com/paulnt04/simple_ping"  
  p.author          = "Paul Panarese"  
  p.email           = "paulnt04@panjunction.com"  
  p.ignore_pattern  = ["tmp/*", "script/*"]  
  p.development_dependencies = []  
end  
  
Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }  
