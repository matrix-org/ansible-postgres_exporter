Vagrant.configure("2") do |config|
  config.vm.box = "debian/stretch64"
  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "vagrant-test.yml"
    ansible.compatibility_mode = "2.0"
#    ansible.config_file = "./ansible.cfg"
  end
end
