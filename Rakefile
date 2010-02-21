$: << File.expand_path("../lib", __FILE__)

require 'rake/testtask'
require 'steam'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |s|
    s.name = "steam"
    s.version = Steam::VERSION
    s.summary = "Headless integration testing w/ HtmlUnit: enables testing JavaScript-driven web sites "
    s.email = "svenfuchs@artweb-design.de"
    s.homepage = "http://github.com/svenfuchs/steam"
    s.description = "Steam is a headless integration testing tool driving HtmlUnit to enable testing JavaScript-driven web sites."
    s.authors = ['Sven Fuchs', 'Clemens Kofler']
    s.files =  FileList["[A-Z]*", "lib/steam.rb", "lib/{core_ext,steam}/**/*", "test/**/*"]

    # TODO depends on rjb
  end
rescue LoadError
  puts "Jeweler, or one of its dependencies, is not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end
