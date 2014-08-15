require 'rake/clean'

desc 'Run jekyll serve with development profile'
task :default do
    system "jekyll serve -w --config _config.yml,_config.dev.yml"
end

desc 'Run jekyll build with development profile'
task :generate do
    system "jekyll build --config _config.yml,_config.dev.yml"
end

CLEAN.include('_site')
