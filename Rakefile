# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks

desc "Post-deploy tasks after creating a Heroku review app."
task :postdeploy => [:"db:setup"] do
  puts " ===> Post-deploy complete!"
end
