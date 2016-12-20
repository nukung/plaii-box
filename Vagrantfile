
# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

    config.vm.box = "plaii-box"
    config.vm.box_url = "http://dev.voicetv.co.th/plaii-box/plaii.box"
    config.vm.network "forwarded_port", guest: 80, host: 8080
    config.vm.hostname = "plaiibox"
    config.vm.synced_folder "public", "/var/www/html", :mount_options => ["dmode=777", "fmode=666"]

end