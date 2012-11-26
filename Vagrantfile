# -*- mode: ruby -*-
# vi: set ft=ruby :
#
# Vagrantfile for ubuntu-12.04-ckbot 
# Require VirtualBox and Vagrant
#
# > cd some_new_directory
# > vagrant box add ckbot git://github.com/ruoranwang/ubuntu-12.04-ckbot.git
# > wget git://github.com/ruoranwang/ubuntu-12.04-ckbot.git/Vagrantfile
# > vagrant up

Vagrant::Config.run do |config|
  config.vm.box = "ckbot"
  config.vm.boot_mode = :gui
  config.vm.customize ["modifyvm", :id, "--memory", 1024]
end
