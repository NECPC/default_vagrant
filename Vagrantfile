# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  # config.vm.box = "hashicorp/precise64"
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "NECPC-Box"
  # config.vm.network :forwarded_port, guest: 80, host: 4567

  # config.vm.network "private_network", ip: "192.168.33.10"

  # config.vm.network "public_network"
  #
  # config.vm.provider "virtualbox" do |vb|
  #   vb.cpus = 2
  #   vb.memory = "2048"
  # end
  #
  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   sudo apt-get install -y apache2 curl
  #   echo "******************* config.vm.provision ***********************"
  # SHELL
  #
  # config.vm.provision :shell, path: "bootstrap.py"
  # config.vm.provision :shell, path: "bootstrap.sh"
end
