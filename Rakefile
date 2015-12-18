task :default => :preview

desc "rebuild the site and start the server"
task :preview do
  system "rm -rf _site"
  system "jekyll serve --watch"
end
