# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "quantal64-rbenv193"
  config.vm.box_url = "~/Dropbox/Public/Vagrant/quantal64-rbenv193.box"
  config.vm.network :hostonly, "192.168.33.10"
  config.vm.share_folder "v-projects", "~/Projects", "~/Projects", :nfs => true
end
