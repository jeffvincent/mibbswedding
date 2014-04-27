guard 'rake', :task => 'build' do
  watch(%r{^_layouts/_haml/*})
  watch(%r{^*.haml})
end

guard 'jekyll-plus', extensions: %w[haml yml sass js md html xml txt rb], serve: true do
  watch(/.*/)
  ignore /^_site/
end

# Guard::Compass
#
# You don't need to configure watchers for guard 'compass' declaration as they generated
# from your Compass configuration file. You might need to define the Compass working directory
# and point to the configuration file depending of your project structure.
#
# Available options:
#
# * :workging_directory => Define the Compass working directory, relative to the Guardfile directory
# * :configuration_file => Path to the Compass configuration file, relative to :project_path
#
# Like usual, the Compass configuration path are relative to the :project_path

# guard 'compass', :project_path => 'not_current_dir', :configuration_file => 'path/to/my/compass_config.rb'
guard :compass
