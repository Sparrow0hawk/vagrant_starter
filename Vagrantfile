# edited down Vagrantfile

Vagrant.configure(2) do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.box_version = "1.0.282"
  config.vm.box_url = "https://vagrantcloud.com/hashicorp/bionic64"
  # run bootstrap.sh when vagrant sets up the VM
  # the file path is relative to the project root (where Vagrantfile is)
  config.vm.provision :shell, path: "bootstrap.sh"
end
