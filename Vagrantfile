Vagrant.require_version ">= 2.0.0"

Vagrant.configure(2) do |config|

 config.vm.box = "bento/ubuntu-18.04"
 config.vm.box_version = "201803.24.0"
 config.ssh.insert_key = false
 config.vm.provision "ansible" do |ansible|
   ansible.verbose = "v"
   ansible.playbook = "site.yml"
 end
end
