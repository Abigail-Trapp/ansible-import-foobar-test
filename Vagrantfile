# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
    # The most common configuration options are documented and commented below.
    # For a complete reference, please see the online documentation at
    # https://docs.vagrantup.com.
  
    # Every Vagrant development environment requires a box. You can search for
    # boxes at https://vagrantcloud.com/search.
    config.vm.box = "ubuntu/trusty64"
  
    # App server 2
    config.vm.define "target1" do |app|
    app.vm.hostname = "orc-target1.test"
    app.vm.network :private_network, ip: "192.168.60.5"
  end
  end
  

# Geerilng, Jeff (2022) ansible-for-devops/orchestration/Vagrantfile
# GitHub. https://github.com/geerlingguy/ansible-for-devops/blob/master/orchestration/Vagrantfile