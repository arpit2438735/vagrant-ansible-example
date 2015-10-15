# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"
BASE_BOX="oracle_63_64"
VAGRANT_BOX_URL = "https://dl.dropbox.com/s/zmitpteca72sjpx/oracle64.box"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box_url= VAGRANT_BOX_URL
  config.vm.box = BASE_BOX

  # config.vm.box_check_update = false
  config.vm.network "private_network", ip: "192.168.50.9"
end
