Vagrant.configure(2) do |config|
  vm_name=['vm1','vm2','vm3']
  vm_name.each do |i|
    config.vm.define "#{i}" do |node|
      node.vm.box = "ubuntu/bionic64"
      node.vm.network "public_network"
      node.vm.hostname = "#{i}"
    end
  end
end
