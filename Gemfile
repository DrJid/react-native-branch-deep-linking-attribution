source "https://rubygems.org"

gem "cocoapods", "~> 1.6"
gem "fastlane", "~> 2.69"
gem "rubocop"
gem "travis"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
