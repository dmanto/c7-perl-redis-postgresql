Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.3"

    config.vm.provision "ansible_local" do |ansible|
      ansible.galaxy_role_file = "requirements.yml"
      ansible.playbook = "playbook.yml"
      ansible.sudo = true
  end  

end
