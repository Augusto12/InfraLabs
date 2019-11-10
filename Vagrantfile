# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define "node1" do |node1|
	node1.vm.box = "ubuntu/xenial64"
	node1.vm.network "private_network", ip: "192.168.33.10"
  end

  config.vm.define "node2" do |node2|	
  	node2.vm.box = "ubuntu/xenial64"
	node2.vm.network "private_network", ip: "192.168.33.11"
  end 

end
