Vagrant.configure("2") do |config|
  config.vm.box = "precise64"

  config.vm.provider "virtualbox" do |provider|
    provider.customize ["storagectl", :id, "--name", "IDE Controller", "--hostiocache","off"]
  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisioning/playbook.yml"
  end
end
