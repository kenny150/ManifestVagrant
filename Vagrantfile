	# # -*- mode: ruby -*-
	# # vi: set ft=ruby :

	# # All Vagrant configuration is done below. The "2" in Vagrant.configure
	# # configures the configuration version (we support older styles for
	# # backwards compatibility). Please don't change it unless you know what
	# # you're doing.
	# Vagrant.configure("2") do |config|
	#   # The most common configuration options are documented and commented below.
	#   # For a complete reference, please see the online documentation at
	#   # https://docs.vagrantup.com.

	#   # Every Vagrant development environment requires a box. You can search for
	#   # boxes at https://vagrantcloud.com/search.
	#   # config.vm.box = "hashcorp/precise64"
	#   config.vm.box = "centos/7"
	#   config.disksize.size = "10GB"
	#   # Execute script called bootstrap.sh ^-^
	#   # config.vm.provision :shell, path: "bootstrap.sh"
	#   # Disable automatic box update checking. If you disable this, then
	#   # boxes will only be checked for updates when the user runs
	#   # `vagrant box outdated`. This is not recommended.
	#   # config.vm.box_check_update = false
	   
	#   # Configurando o provisionador ^-^
	#   #  config.vm.provider "vmware_fusion"
	#     config.vm.provider "virtualbox"
	#   # Create a forwarded port mapping which allows access to a specific port
	#   # within the machine from a port on the host machine. In the example below,
	#   # accessing "localhost:8080" will access port 80 on the guest machine.
	#   # NOTE: This will enable public access to the opened port
	#    # config.vm.network "forwarded_port", guest: 80, host: 8088

	#   # Create a forwarded port mapping which allows access to a specific port
	#   # within the machine from a port on the host machine and only allow access
	#   # via 127.0.0.1 to disable public access
	#   # config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1"

	#   # Create a private network, which allows host-only access to the machine
	#   # using a specific IP.
	#    config.vm.network "private_network", ip: "192.168.33.10"

	#   # Create a public network, which generally matched to bridged network.
	#   # Bridged networks make the machine appear as another physical device on
	#   # your network.
	#   # config.vm.network "public_network"

	#   # Share an additional folder to the guest VM. The first argument is
	#   # the path on the host to the actual folder. The second argument is
	#   # the path on the guest to mount the folder. And the optional third
	#   # argument is a set of non-required options.
	#    # config.vm.synced_folder "../data", "/vagrant_data"
	#    # config.vm.synced_folder "data", "/vagrant_data"

	#   # Provider-specific configuration so you can fine-tune various
	#   # backing providers for Vagrant. These expose provider-specific options.
	#   # Example for VirtualBox:
	#   #
	#    config.vm.provider "virtualbox" do |vb|
	#   #   # Display the VirtualBox GUI when booting the machine
	#   #   vb.gui = true
	#   #
	#   #   # Customize the amount of memory on the VM:
	#      vb.memory = "1024"
	#    end
	  
	#       # Define name of host ^-^
	#    config.vm.define "host1"
	#   #
	#   # View the documentation for the provider you are using for more
	#   # information on available options.

	#   # Enable provisioning with a shell script. Additional provisioners such as
	#   # Puppet, Chef, Ansible, Salt, and Docker are also available. Please see the
	#   # documentation for more information about their specific syntax and use.
	#    config.vm.provision "shell", inline: <<-SHELL
	#    		yum update && yum install -y epel-release
	# 	   	yum install telnet curl wget git net-tools -y
	# 	SHELL
	# end


Vagrant.configure("2") do |vm2|
	vm2.vm.box = "centos/7"
	vm2.disksize.size = "10GB"
	vm2.vm.provider "virtualbox"
	vm2.vm.network "private_network", ip: "192.168.33.11"
	# vm2.vm.synced_folder "data", "/vagrant_data"
	vm2.vm.provider "virtualbox" do |vb2|
		vb2.memory = "1024"
	end
    vm2.vm.define "host2"
    vm2.vm.provision "shell", inline: <<-SHELL
	   yum update && yum install -y epel-release
	   yum install telnet curl wget git net-tools -y
	SHELL
end

Vagrant.configure("2") do |vm3|
	vm3.vm.box = "centos/7"
	vm3.disksize.size = "10GB"
	vm3.vm.provider "virtualbox"
	vm3.vm.network "private_network", ip: "192.168.33.12"
	# vm3.vm.synced_folder "data", "/vagrant_data"
	vm3.vm.provider "virtualbox" do |vb3|
		vb3.memory = "1024"
	end
    vm3.vm.define "host3"
    vm3.vm.provision "shell", inline: <<-SHELL
	   yum update && yum install -y epel-release
	   yum install telnet curl wget git net-tools -y
	SHELL
end

Vagrant.configure("2") do |vm4|
	vm4.vm.box = "centos/7"
	vm4.disksize.size = "10GB"
	vm4.vm.provider "virtualbox"
	vm4.vm.network "private_network", ip: "192.168.33.13"
	# vm4.vm.synced_folder "data", "/vagrant_data"
	vm4.vm.provider "virtualbox" do |vb4|
		vb4.memory = "1024"
	end
    vm4.vm.define "host4"
    vm4.vm.provision "shell", inline: <<-SHELL
	   yum update && yum install -y epel-release
	   yum install telnet curl wget git net-tools -y
	SHELL
end