require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('life-fitness-grapher', '0.0.1') do |p|
  p.description    = "Creates graphs out of data from Life Fitness machines."
  p.url            = ""
  p.author         = "Mike Skalnik"
  p.email          = "mike.skalnik@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
