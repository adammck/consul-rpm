Vagrant.configure(2) do |config|
  config.vm.box = ENV.fetch("BUILD_BOX", "bento/centos-7.1")
  config.vm.provision "shell", inline: "/vagrant/bin/provision", privileged: false
end
