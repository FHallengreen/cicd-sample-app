# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.hostname = "FrederikLinux"

  config.vm.box = "bento/ubuntu-22.04"

config.vm.network "forwarded_port", guest: 80, host: 8080

config.vm.network "forwarded_port", guest: 22, host: 2222, protocol: "tcp"

config.vm.network "private_network", ip: "192.168.56.20", subnet: "255.255.255.0", gateway: "192.168.56.1"

end
