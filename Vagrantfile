# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "rbenv-2GB"
  config.vm.box_url = "https://dl.dropbox.com/u/6154794/Vagrant/rbenv-2GB.box"
  config.vm.network :hostonly, "192.168.33.10"
  config.vm.share_folder "v-sample_app", "~/sample_app", "~/Projects/sample_app", :nfs => true
end
