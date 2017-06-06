
  # -*- mode: ruby -*-
  # vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_check_update = false


  config.vm.define "dev1" do |dev1|
      dev1.vm.network  "private_network", ip: "192.168.1.160"
      dev1.vm.hostname = "dev1"
      dev1.vm.provider "virtualbox" do |vb|
         vb.memory = "1024"
      end
  end

  
 config.vm.define "dev2" do |dev2|
     dev2.vm.network "private_network", ip: "192.168.1.161"
     dev2.vm.hostname = "dev2"  
     dev2.vm.provider "virtualbox" do |vb|
         vb.memory = "1024"
     end
 end

 
end
