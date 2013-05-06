# Debian 7.0 "Wheezy" for Vagrant

Add the box to your local vagrant :

	vagrant box add 'debian-70' https://raw.github.com/gmoigneu/vagrant-debian-wheezy-box/master/debian-70.box
	
Define in your Vagrantfile the box to be used :

	config.vm.box = "debian-70"
	config.vm.box_url = "https://raw.github.com/gmoigneu/vagrant-debian-wheezy-box/master/debian-70.box"
	

For a complete LAMP stack based on this box, consult the [vagrant-lamp-debian7](https://github.com/gmoigneu/vagrant-lamp-debian7) repository.