Vagrant.configure(2) do |config|
  config.vm.define "control" do |control|
    control.vm.box = "ubuntu/trusty64"
    control.vm.network "private_network", ip: "192.168.0.2"
    control.vm.hostname = "control"
  end
  config.vm.define "app01" do |app01|
    app01.vm.box = "ubuntu/trusty64"
    app01.vm.network "private_network", ip: "192.168.0.3"
    app01.vm.hostname = "app01"
  end
  config.vm.define "app02" do |app02|
    app02.vm.box = "ubuntu/trusty64"
    app02.vm.network "private_network", ip: "192.168.0.4"
    app02.vm.hostname = "app02"
  end
  config.vm.define "db01" do |db01|
    db01.vm.box = "ubuntu/trusty64"
    db01.vm.network "private_network", ip: "192.168.0.5"
    db01.vm.hostname = "db01"
  end
  config.vm.define "lb01" do |lb01|
    lb01.vm.box = "ubuntu/trusty64"
    lb01.vm.network "private_network", ip: "192.168.0.10"
    lb01.vm.hostname = "lb01"
  end
end
