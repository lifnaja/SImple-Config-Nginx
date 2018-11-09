Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network "private_network", ip: "192.168.33.94"
  config.vm.synced_folder "src/", "/src/website"
end
