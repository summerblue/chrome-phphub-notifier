namespace :chrome do
  desc 'build chrome zip file'
  task :zip do
    puts 'building zip for chrome...'
    sh %{ zip -r chrome-phphub-notifier.zip _locales/ manifest.json *.png *.js *.html *.css }
    puts 'build done.'
  end
end

task default: 'chrome:zip'

