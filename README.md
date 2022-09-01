# vagrant-virtualbox

### Install Virtual Box
```bash
sudo apt update
sudo apt install virtualbox
sudo apt install virtualbox virtualbox-ext-pack
```

### Install Vagrant 

Download the Vagrant package with wget :
```bash
curl -O https://releases.hashicorp.com/vagrant/2.2.9/vagrant_2.2.9_x86_64.deb
```
Once the file is downloaded, install it by typing:
```bash
sudo apt install ./vagrant_2.2.9_x86_64.deb
vagrant --version
```

### Verify
```bash
mkdir ~/my-vagrant-project
cd ~/my-vagrant-project
```

we will use the centos/8 box:
```bash
vagrant init centos/8
vagrant up
```

To ssh into the virtual machine, run:
```bash
vagrant ssh
```

We can stop the virtual machine with the following command:
```bash
vagrant halt
```

To destroy all resources created during the creation of the machine, enter:
```bash
vagrant destroy
```
