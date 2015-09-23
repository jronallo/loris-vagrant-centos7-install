# Install Loris in Vagrant CentOS 7

In order to test what would be required to install Loris on a RHEL 7 server, I tested it out in a CentOS 7 Vagrant box. This includes a demo OpenSeadragon page.

The most interesting file will be loris-vagrant-install.sh which is a Bash script with all the steps necessary install under CentOS 7. Hopefully this hepls anyone that has to deploy Loris under RHEL 7.

## Installation

You must have Vagrant installed.

```
git clone https://github.com/jronallo/loris-vagrant-centos7-install.git
cd loris-vagrant-centos7-install
vagrant up
vagrant ssh
/vagrant/loris-vagrant-install.sh
```
