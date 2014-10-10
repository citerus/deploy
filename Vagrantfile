# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "shopping" do |shopping|
    shopping.vm.box = "hashicorp/precise32"
    shopping.vm.network "private_network", ip: "10.0.1.10"
  end

  config.vm.define "order" do |order|
    order.vm.box = "hashicorp/precise32"
    order.vm.network "private_network", ip: "10.0.1.20"
  end

  config.vm.define "productcatalog" do |productcatalog|
    productcatalog.vm.box = "hashicorp/precise32"
    productcatalog.vm.network "private_network", ip: "10.0.1.30"
  end
end
