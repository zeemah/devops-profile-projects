# Manual Provisioning Project Setup 

#### Prerequisite
    1. Oracle VM Virtualbox
    2. Vagrant
    3. Vagrant plugins
        a. vagrant plugin install vagrant-hostmanager
        b. vagrant plugin install vagrant-vbguest
    4. Git bash or equivalent editor

#### VM SETUP
    1. Clone source code.
    2. Cd into the repository.
    3. Switch to the local-setup branch.
    4. cd into vagrant/manual-provisioning.

Bring up vm’s
    " $ vagrant up "

NOTE: Bringing up all the vm’s may take a long time based on various factors.
If vm setup stops in the middle run “vagrant up” command again.

INFO: All the vm’s hostname and /etc/hosts file entries will be automatically updated.