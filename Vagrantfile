
Vagrant.configure("2") do |config|
  config.vm.box = "debian/stretch64"
  config.vm.network :public_network, bridge: "en0: Wi-Fi (AirPort)"
  config.vm.provider "virtualbox" do |v|
     v.customize ["modifyvm", :id, "--memory", 2048, "--cpus", 2, "--name", "linux-setup"]
  end
end
