# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "sqlserver2016"
  config.ssh.username = "vagrant"
  config.ssh.password = "vagrant"
  config.vm.network "forwarded_port", guest: 1433, host: 4203
end
