# Why a Demo?

    This is a set of demo "vagrant based hosts/environments" to provide quick starting points for using Vault. You will need Vagrant <a href="https://vagrantup.com">https://vagrantup.com</a> installed and working with VirtualBox <a href="https://virtualbox.org/">https://virtualbox.org/</a>. ( Other VM providers should work too, but for now these examples are designed only for Virtualbox.)

To get started, you select which demo you want.

1. ../from-source-dev

    This is a single Vault vm for use in DEV mode. The host is based on the "ubuntu/trusty64" image and will build vault from current source.

2. ../HA-example
	
    This is a set of 4 seperate VM's. 
    There are two Vault hosts that uses two Consul hosts to provide HA support.
	The two Vault hosts are exposed to only the guest OS by default.
		(The Consul hosts are only exposed to the Vault hosts.)

Please see the README's in the respective directories for details.

However, in general:
	cd into the directory.
	run "vagrant up" to start the vm's.

