# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

    config.vm.box = "bento/ubuntu-20.04"
    config.vm.hostname = "vagrant"
    config.vm.network "forwarded_port", guest: 80, host: 8081
    config.vm.network "forwarded_port", guest: 5432, host: 5432
    config.vm.network "forwarded_port", guest: 27017, host: 27017
    config.vm.network "forwarded_port", guest: 9000, host: 9000
    config.vm.network "forwarded_port", guest: 6379, host: 6379
    config.vm.network "forwarded_port", guest: 3000, host: 3000
    config.vm.network "forwarded_port", guest: 5000, host: 5000
    config.vm.network "forwarded_port", guest: 7000, host: 7000
    config.vm.network "forwarded_port", guest: 4566, host: 4566
    config.vm.network "forwarded_port", guest: 9042, host: 9042
    config.vm.network "private_network", ip: "192.168.33.10"
end
