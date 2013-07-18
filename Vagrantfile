# -*- mode: ruby -*-
# vi: set ft=ruby :
# This is a Vagrant configuration file. It can be used to set up and manage
# virtual machines on your local system or in the cloud. See http://downloads.vagrantup.com/
# for downloads and installation instructions, and see http://docs.vagrantup.com/v2/
# for more information and configuring and using Vagrant.

Vagrant.configure("2") do |config|
  # All Vagrant configuration is done here. The most common configuration
  # options are documented and commented below. For a complete reference,
  # please see the online documentation at vagrantup.com.
  
  # Create a forwarded port mapping which allows access to a specific port
  # within the machine from a port on the host machine. In the example below,
  # accessing "localhost:8080" will access port 80 on the guest machine.
  # config.vm.network :forwarded_port, guest: 80, host: 8080
  
  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  # config.vm.network :private_network, ip: "192.168.33.10"
  
  # Create a public network, which generally matched to bridged network.
  # Bridged networks make the machine appear as another physical device on
  # your network.
  # config.vm.network :public_network
  
  # Share an additional folder to the guest VM. The first argument is
  # the path on the host to the actual folder. The second argument is
  # the path on the guest to mount the folder. And the optional third
  # argument is a set of non-required options.
  # config.vm.synced_folder "../data", "/vagrant_data"
  
  # Provider-specific configuration so you can fine-tune various
  # backing providers for Vagrant. These expose provider-specific options.
  # Example for VirtualBox:
  
  # config.vm.provider :virtualbox do |vb|
  #   # Don't boot with headless mode
  #   vb.gui = true
  # 
  #   # Use VBoxManage to customize the VM. For example to change memory:
  #   vb.customize ["modifyvm", :id, "--memory", "1024"]
  # end
    
  # View the documentation for the provider you're using for more
  # information on available options.
  
  # Enable provisioning with chef solo, specifying a cookbooks path, roles
  # path, and data_bags path (all relative to this Vagrantfile), and adding
  # some recipes and/or roles.
  #
  # config.vm.provision :chef_solo do |chef|
  #   chef.cookbooks_path = "cookbooks"
  #   chef.roles_path = "roles"
  #   chef.data_bags_path = "data_bags"
  #   chef.add_recipe "mysql"
  #   chef.add_role "web"
  #
  #   # You may also specify custom JSON attributes:
  #   chef.json = { :mysql_password => "foo" }
  # end

  # Enable provisioning with chef server, specifying the chef server URL,
  # and the path to the validation key (relative to this Vagrantfile).
  #
  # The Opscode Platform uses HTTPS. Substitute your organization for
  # ORGNAME in the URL and validation key.
  #
  # If you have your own Chef Server, use the appropriate URL, which may be
  # HTTP instead of HTTPS depending on your configuration. Also change the
  # validation key to validation.pem.
  #
  # config.vm.provision :chef_client do |chef|
  #   chef.chef_server_url = "https://api.opscode.com/organizations/ORGNAME"
  #   chef.validation_key_path = "ORGNAME-validator.pem"
  # end
  #
  # If you're using the Opscode platform, your validator client is
  # ORGNAME-validator, replacing ORGNAME with your organization name.
  #
  # If you have your own Chef Server, the default validation client name is
  # chef-validator, unless you changed the configuration.
  #
  #   chef.validation_client_name = "ORGNAME-validator"
  
	config.vm.define :precise32 do |precise32|
    # Every Vagrant virtual environment requires a box to build off of.
    precise32.vm.box = "precise32"
  
    # The url from where the 'precise32.vm.box' box will be fetched if it
    # doesn't already exist on the user's system.
    precise32.vm.box_url = "http://files.vagrantup.com/precise32.box"
  end

	config.vm.define :precise64 do |precise64|
    # Every Vagrant virtual environment requires a box to build off of.
    precise64.vm.box = "precise64"
  
    # The url from where the 'precise64.vm.box' box will be fetched if it
    # doesn't already exist on the user's system.
    precise64.vm.box_url = "http://files.vagrantup.com/precise64.box"
  end

	config.vm.define :lucid32 do |lucid32|
    # Every Vagrant virtual environment requires a box to build off of.
    lucid32.vm.box = "lucid32"
  
    # The url from where the 'lucid32.vm.box' box will be fetched if it
    # doesn't already exist on the user's system.
    lucid32.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  end

	config.vm.define :lucid64 do |lucid64|
    # Every Vagrant virtual environment requires a box to build off of.
    lucid64.vm.box = "lucid64"
  
    # The url from where the 'lucid64.vm.box' box will be fetched if it
    # doesn't already exist on the user's system.
    lucid64.vm.box_url = "http://files.vagrantup.com/lucid64.box"
  end
end
