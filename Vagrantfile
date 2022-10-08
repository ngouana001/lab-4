RAM = 2048
CPU = 2
IP = "10.0.0.10"

Vagrant.configure("2") do |config|
  config.vm.box = "geerlingguy/centos7"
  config.vm.network "private_network", ip: IP
  config.vm.provider "virtualbox" do |v|
  v.memory = 2048
  v.cpus = 2
  end
end
