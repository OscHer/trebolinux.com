# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
   config.vm.box              = "bento/ubuntu-24.04"
   config.vm.box_check_update = false
   config.vm.hostname         = "trebolinuxdev"

   config.vm.provider :libvirt do |libvirt|
      libvirt.memory           = 2048
      libvirt.cpus             = 2
   end

end
