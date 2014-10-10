# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "shopping" do |shopping|
    shopping.vm.box = "hashicorp/precise32"
    shopping.vm.network "private_network", ip: "10.0.1.1"
  end

  config.vm.define "order" do |order|
    order.vm.box = "hashicorp/precise32"
    order.vm.network "private_network", ip: "10.0.1.2"
  end

  config.vm.define "product" do |product|
    product.vm.box = "hashicorp/precise32"
    product.vm.network "private_network", ip: "10.0.1.3"
  end
end
