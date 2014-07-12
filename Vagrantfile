#!/usr/bin/env ruby

Vagrant.configure('2') do |config|
  config.vm.provider 'docker' do |d|
    d.build_dir = '.'
    d.ports = ['8000:80']
  end
end

