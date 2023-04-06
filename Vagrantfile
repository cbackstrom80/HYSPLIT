Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64" # Ubuntu 18.04 LTS
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = "2"
  end
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbooks/hysplit-playbook.yml" # Change to your Ansible playbook file name
  end
  
end

