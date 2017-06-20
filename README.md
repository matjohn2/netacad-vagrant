# netacad-vagrant

Vagrant environment for netacad devops training June 19th - 23rd.

## Install

1. Get Vagrant
[https://releases.hashicorp.com/vagrant/1.9.5/vagrant_1.9.5_x86_64.dmg](https://releases.hashicorp.com/vagrant/1.9.5/vagrant_1.9.5_x86_64.dmg)

On WASTC Mac's you will need to wait until ICT has installed vagrant for you.

Check on a terminal using ```which vagrant``` Output should show ```/usr/local/bin/vagrant```.


2. Get the 'Vagrantfile' from this repository.
```
mkdir ~/netacad-vagrant
cd ~/netacad-vagrant
curl https://raw.githubusercontent.com/matjohn2/netacad-vagrant/master/Vagrantfile -o Vagrantfile
```
3. ```vagrant up```

## Use

```vagrant ssh``` once provisioning is complete to access the VM's shell.

Doing everything inside the ```/vagrant``` directory in the VM will make the contents available to the host OS (in whatever directory you did the ```vagrant up```) meaning you will be able to use a graphical text editor from the mac if you prefer when we are doing the coding/hands on/git excercises.

Changes made on the mac will be reflected in the VM.
