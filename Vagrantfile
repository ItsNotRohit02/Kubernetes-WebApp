Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu2204"
  config.vm.network "private_network", ip: "192.168.33.20"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "6144"
    vb.cpus = 6
  end
end
