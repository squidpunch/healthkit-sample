# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'healthkit-sample'


  app.entitlements['com.apple.developer.healthkit'] = true
  app.weak_frameworks += ['HealthKit']

  app.deployment_target = "7.1"
  app.sdk_version = "8.1"
end
