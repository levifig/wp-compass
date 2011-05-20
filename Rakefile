# Edit this file and run "rake deploy" to push your theme to your server
# You need to have the rake gem and rsync installed on your system, obviously! :)
#
ssh_user = "user@domain.com" # for rsync deployment
remote_root = "/var/www/path-to/wordpress/wp-content/themes/themename" # for rsync deployment

desc "Deploys the theme"
task :deploy do
  puts "*** Deploying the site ***"
  system("rsync -avz --delete . #{ssh_user}:#{remote_root}")
end
