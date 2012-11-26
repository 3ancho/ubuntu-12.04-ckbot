# -*- mode: ruby -*-
# vi: set ft=ruby :
#
# Vagrantfile for ubuntu-12.04-ckbot 
# Require VirtualBox and Vagrant
#
# Note: If using windows, in step 3 you need to download the Vagrantfile.
#
# 1> cd some_new_directory
# 2> vagrant box add ckbot git://github.com/ruoranwang/ubuntu-12.04-ckbot.git
# 3> wget https://raw.github.com/ruoranwang/ubuntu-12.04-ckbot/master/Vagrantfile
# 4> vagrant up


Vagrant::Config.run do |config|
  config.vm.box = "ckbot"
  config.vm.boot_mode = :gui
  config.vm.customize ["modifyvm", :id, "--memory", 1024]
end
