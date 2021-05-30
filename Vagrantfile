Vagrant.configure(2) do |config|
  vm_name=['docker1','docker2','docker3']
  vm_name.each do |i|
    config.vm.define "#{i}" do |node|
      node.vm.box = "ubuntu/bionic64"
      node.vm.network "public_network"
      node.vm.hostname = "#{i}"
    end
  end
end