# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "debian/contrib-jessie64"
  config.vm.box_version = "~> 8.7.0"
  config.vm.provision :shell, :path => "install/install.sh"
end
