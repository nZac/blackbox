# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.hostname = "com.debops.dev"

    config.vm.box = "rafacas/debian76-plain"
    config.vm.network "private_network", ip: "192.168.30.30"
end
