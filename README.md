# wildfly-vagrant
A Vagrant File for wildfly 8 (install JDK7)

Download a wildfly vagrant configured for a link: https://drive.google.com/open?id=0Bx5VjHTESJ_xM05UaEtybFNDcUU

Extract wildfly-8-vagrant-version on the same folder of the VagrantFile

To setup your box just run "vagrant up"
After provision, you can run "vagrant ssh" for connect to the box
Finally, inside of the box you can run "sudo service wildfly start" for to start the service

Cause you're need change the forward port editing "VagrantFile"
