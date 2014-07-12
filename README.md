vagrant-dev
===========

Vagrant dev environment

Requirements
------------

- [VirtualBox ](http://www.vagrantup.com/)
- [Vagrant](http://www.vagrantup.com/) (duh)
- [Vagrant Omnibus](https://github.com/schisamo/vagrant-omnibus)
- [Git client](http://git-scm.com/)

Installation
------------

1. Clone repository

	$ git clone https://github.com/kozie/vagrant-dev.git

2. Initialize the cookbooks

	$ git submodule init
	$ git submodule update

3. Run Vagrant and let it do it's magic

	$ vagrant up