# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  # CentOS 7.2 64-bit (amd64/x86_64), Puppet Enterprise 3.8.4 (agent)
  # config.vm.box = "puppetlabs/centos-7.2-64-puppet-enterprise"
  # CentOS 7.2 64-bit (amd64/x86_64), Puppet 4.3.2 / Puppet Enterprise 2015.3.2 (agent)
  config.vm.box = "puppetlabs/centos-7.2-64-puppet"

  # config.vm.network "forwarded_port", guest: 80, host: 8080
  # config.vm.network "private_network", ip: "192.168.33.10"
  # config.vm.synced_folder "../data", "/vagrant_data"

  # config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end

  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   sudo apt-get install -y apache2
  # SHELL
end