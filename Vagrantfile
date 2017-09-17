
# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

$script = <<-SCRIPT
echo "-----BEGIN RSA PRIVATE KEY-----
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
-----END RSA PRIVATE KEY-----" >> /home/vagrant/.ssh/id_rsa
chmod 0600 /home/vagrant/.ssh/id_rsa
chown vagrant.vagrant /home/vagrant/.ssh/id_rsa
SCRIPT

$script2 = <<-SCRIPT
echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC0I4zY6dqOKkL+kjCpucO7x9ggip+gTEtTzHtQUWs6MZ0oL4qGPPXbStohFUkUd7ix4piOJL9S0li4JNIsZFjrZpk5QRhb9zq3q7T0IkId/XeQCZiB6F4wS9UcJELJDSN/Rwtl1J2p7HD+cklmdaDDvyrCP6S9/x/O5b0q4OfKnRzYbrkoSjeXl/AuqKs0tF3T995+5Qvstu8b6deAryYJble3krDo6GYLIapFFwlcHQsc32M6yWyGhqembGHWWvdBiGGK0Y3xttjx+5sbadd3cyVqXSJUDHYeXFin8/JlLCFL0r9RLltwb/uaYEqGsoZBxcvZE819YeTsLNA4gEdDs0vVqCwMu9HqH3An2wIHP9U8Ukw8SSObdJmAP1SYMMK/95I7BJrffNonmfsQhVCt6/cNrSRePiQ5WUjkEmvNophwqT/tTavzniAaIoXkNb+X/i2Wo0VXLx+zqxp6RVHWOjZ5MPvqizn1XeH+ikeAyxC1ixw2AxxoxjENhRcqt93RJn9zpvbbFRDbk/jome35wdYye+pD4AQwwcZD0vUExWsVRW4xmmsPwVp/KU4mg96czRakBR8bB/LjBhCcX08mXOfg67MA38OQnDzB5wFWYWbdX+7X2jo0JLBE7NnlqBVSCZLlA3JpA9Ev0zR2kcUPwberHwJ4xmIQtbSeIUOy+Q== ansimaster" >> /home/vagrant/.ssh/authorized_keys
SCRIPT


 
  config.vm.define "web01", primary: true do |web01|

    web01.vm.provision "shell", inline: $script2, privileged: true     
    
    web01.vm.box = "ubuntu/trusty64"
    web01.vm.hostname = 'web01'
    web01.vm.box_url = "ubuntu/trusty64"

    web01.vm.network "public_network", :bridge => "en0: Wi-Fi (AirPort)"
    web01.vm.network "private_network", ip: "10.10.10.11"

    web01.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 512]
      v.customize ["modifyvm", :id, "--name", "web01"]
    end
  end

  config.vm.define "web02" do |web02|

    web02.vm.provision "shell", inline: $script2, privileged: true 

    web02.vm.box = "ubuntu/trusty64"
    web02.vm.hostname = 'web02'
    web02.vm.box_url = "ubuntu/trusty64"

    web02.vm.network "public_network", :bridge => "en0: Wi-Fi (AirPort)"
    web02.vm.network "private_network", ip: "10.10.10.12"

    web02.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 512]
      v.customize ["modifyvm", :id, "--name", "web02"]
    end
  end

  config.vm.define "web03" do |web03|

    web03.vm.provision "shell", inline: $script2, privileged: true    

    web03.vm.box = "ubuntu/trusty64"
    web03.vm.hostname = 'web03'
    web03.vm.box_url = "ubuntu/trusty64"

    web03.vm.network "public_network", :bridge => "en0: Wi-Fi (AirPort)"
    web03.vm.network "private_network", ip: "10.10.10.13"

    web03.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 512]
      v.customize ["modifyvm", :id, "--name", "web03"]
    end
  end

  config.vm.define "ansimaster" do |ansimaster|

    ansimaster.vm.provision "shell", path: "Scripts/ansible.sh"

    ansimaster.vm.provision "shell", inline: $script, privileged: true

    ansimaster.vm.box = "ubuntu/trusty64"
    ansimaster.vm.hostname = 'ansimaster'
    ansimaster.vm.box_url = "ubuntu/trusty64"

    ansimaster.vm.network "public_network", :bridge => "en0: Wi-Fi (AirPort)"
    ansimaster.vm.network "private_network", ip: "10.10.10.10"

    ansimaster.vm.provider :virtualbox do |v|
      v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
      v.customize ["modifyvm", :id, "--memory", 512]
      v.customize ["modifyvm", :id, "--name", "ansimaster"]
    end
  end

end
