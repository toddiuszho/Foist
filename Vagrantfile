Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision :shell, path: "rvm/install-rvm.sh", args: "stable", privileged: false
  config.vm.provision :shell, path: "rvm/install-ruby.sh", args: "2.5.0 aws-sdk bundler faraday haml rubocop", privileged: false
end
