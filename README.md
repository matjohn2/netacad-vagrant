# netacad-vagrant

Vagrant environment for netacad devops training June 19th - 23rd.

## Install

1. Get Vagrant
[https://releases.hashicorp.com/vagrant/1.9.5/vagrant_1.9.5_x86_64.dmg]()

2. Get the 'Vagrantfile' from this repository.
```
wget https://raw.githubusercontent.com/matjohn2/netacad-vagrant/master/Vagrantfile 
```
3. ```vagrant up```

## Use

```vagrant ssh``` once provisioning is complete to access the VM's shell.

Doing everything inside the ```/vagrant``` directory in the VM will make the contents available to the host OS (in whatever directory you did the ```vagrant up```) meaning you will be able to use a graphical text editor from the mac if you prefer when we are doing the coding/hands on/git excercises.

Changes made on the mac will be reflected in the VM.

