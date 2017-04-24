require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('samplify', '0.1.0') do |p|
  p.description    = "Generate a unique token with Active Record."
  p.url            = "https://github.com/shanmugarajan/samplify"
  p.author         = "Shan"
  p.email          = "shanvinobe@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }