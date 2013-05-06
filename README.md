# Debian 7.0 "Wheezy" for Vagrant

Add the box to your local vagrant :

	vagrant box add 'debian-70' https://static.nls.io/debian-70.box
	
Define in your Vagrantfile the box to be used :

	config.vm.box = "debian-70"
	config.vm.box_url = "https://static.nls.io/debian-70.box"

You can also clone this repository and add your local box directly.	

For a complete LAMP stack based on this box, consult the [vagrant-lamp-debian7](https://github.com/gmoigneu/vagrant-lamp-debian7) repository.