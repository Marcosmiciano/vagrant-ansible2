Vagrant.configure("2") do |config|

config.vm.provider "virtualbox" do |v|
  v.name = "VAGRANT-THOR"
  v.memory = "1024"
  v.cpus = "1"
end

  config.vm.box = "ubuntu/focal64" 
  config.vm.network "public_network", ip: "192.168.10.101", bridge:"Intel(R) Wireless-AC 9560"

end
