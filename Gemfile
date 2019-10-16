source 'https://rubygems.org'

plugin 'bootboot', '~> 0.1.1'
Plugin.send(:load_plugin, 'bootboot') if Plugin.installed?('bootboot')

if ENV['DEPENDENCIES_NEXT']
  enable_dual_booting if Plugin.installed?('bootboot')

  gem 'minitest', "~> 5.12"
else
  gem 'minitest', "~> 4.7"
end

gem 'rake', '~> 10.0'
