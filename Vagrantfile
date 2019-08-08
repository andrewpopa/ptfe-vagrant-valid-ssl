# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "alvaro/bionic64"
  config.vm.network "private_network", ip: "192.168.56.20"
  config.vm.hostname = "ptfe"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"
    vb.cpus = "2"
  end
end
